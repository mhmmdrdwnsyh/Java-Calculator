import java.awt.EventQueue;

import javax.swing.JFrame;
import javax.swing.JTextField;
import java.awt.BorderLayout;
import javax.swing.JButton;
import java.awt.event.ActionListener;
import java.awt.event.ActionEvent;
import java.awt.Font;
import java.awt.Color;
import javax.swing.SwingConstants;
import java.awt.SystemColor;
import javax.swing.UIManager;

public class Project_kalkulator {

	private JFrame frame;
	private JTextField textField;
	private JButton btn00;
	
		double first;
		double second;
		double result;
		String operation;
		String answer;

	/**
	 * Launch the application.
	 */
	public static void main(String[] args) {
		EventQueue.invokeLater(new Runnable() {
			public void run() {
				try {
					Project_kalkulator window = new Project_kalkulator();
					window.frame.setVisible(true);
				} catch (Exception e) {
					e.printStackTrace();
				}
			}
		});
	}

	/**
	 * Create the application.
	 */
	public Project_kalkulator() {
		initialize();
	}

	/**
	 * Initialize the contents of the frame.
	 */
	private void initialize() {
		frame = new JFrame();
		frame.getContentPane().setForeground(new Color(0, 0, 0));
		frame.getContentPane().setBackground(new Color(0, 0, 0));
		frame.setBounds(100, 100, 306, 462);
		frame.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);
		frame.getContentPane().setLayout(null);
		
		textField = new JTextField();
		textField.setBackground(Color.WHITE);
		textField.setForeground(Color.BLACK);
		textField.setFont(new Font("Trebuchet MS", Font.PLAIN, 11));
		textField.setHorizontalAlignment(SwingConstants.LEFT);
		textField.setBounds(8, 11, 272, 63);
		frame.getContentPane().add(textField);
		textField.setColumns(10);
		
		final JButton btnClear = new JButton("C");
		btnClear.addActionListener(new ActionListener() {
			public void actionPerformed(ActionEvent e) 
			{
				textField.setText(null);
			}
		});
		btnClear.setForeground(new Color(255, 165, 0));
		btnClear.setBackground(Color.GRAY);
		btnClear.setFont(new Font("Arial", Font.BOLD, 21));
		btnClear.setBounds(80, 85, 60, 56);
		frame.getContentPane().add(btnClear);
		
		final JButton btnDot = new JButton(".");
		btnDot.setForeground(new Color(255, 255, 255));
		btnDot.setBackground(Color.DARK_GRAY);
		btnDot.setFont(new Font("Arial", Font.BOLD, 21));
		btnDot.addActionListener(new ActionListener() {
			public void actionPerformed(ActionEvent e) {
				String number=textField.getText()+btnDot.getText();
				textField.setText(number);
			}
		});
		btnDot.setBounds(8, 356, 60, 56);
		frame.getContentPane().add(btnDot);
		
		final JButton btnequal = new JButton("=");
		btnequal.setForeground(new Color(255, 255, 255));
		btnequal.setBackground(new Color(255, 165, 0));
		btnequal.setFont(new Font("Arial", Font.BOLD, 21));
		btnequal.addActionListener(new ActionListener() {
			public void actionPerformed(ActionEvent e) 
			{
				String answer;
				second=Double.parseDouble(textField.getText());
				if(operation=="+")
				{
					result=first+second;
					answer=String.format("%.2f", result);
					textField.setText(answer);
				}
				else if(operation=="-")
				{
					result=first-second;
					answer=String.format("%.2f", result);
					textField.setText(answer);
				}
				else if(operation=="*")
				{
					result=first*second;
					answer=String.format("%.2f", result);
					textField.setText(answer);
				}
				else if(operation=="/")
				{
					result=first/second;
					answer=String.format("%.2f", result);
					textField.setText(answer);
				}	
			}
		});
		btnequal.setBounds(220, 289, 60, 123);
		frame.getContentPane().add(btnequal);
		
		final JButton btn1 = new JButton("1");
		btn1.setForeground(new Color(255, 255, 255));
		btn1.setBackground(Color.DARK_GRAY);
		btn1.setFont(new Font("Arial", Font.BOLD, 21));
		btn1.addActionListener(new ActionListener() {
			public void actionPerformed(ActionEvent e) {
				String number=textField.getText()+btn1.getText();
				textField.setText(number);
			}
		});
		btn1.setBounds(8, 289, 60, 56);
		frame.getContentPane().add(btn1);
		
		final JButton btn2 = new JButton("2");
		btn2.addActionListener(new ActionListener() {
			public void actionPerformed(ActionEvent e) 
			{
				String number=textField.getText()+btn2.getText();
				textField.setText(number);
			}
		});
		btn2.setForeground(new Color(255, 255, 255));
		btn2.setBackground(Color.DARK_GRAY);
		btn2.setFont(new Font("Arial", Font.BOLD, 21));
		btn2.setBounds(80, 289, 60, 56);
		frame.getContentPane().add(btn2);
		
		final JButton btn3 = new JButton("3");
		btn3.addActionListener(new ActionListener() {
			public void actionPerformed(ActionEvent e)
			{
				String number=textField.getText()+btn3.getText();
				textField.setText(number);
			}
		});
		btn3.setForeground(new Color(255, 255, 255));
		btn3.setBackground(Color.DARK_GRAY);
		btn3.setFont(new Font("Arial", Font.BOLD, 21));
		btn3.setBounds(150, 289, 60, 56);
		frame.getContentPane().add(btn3);
		
		final JButton btn4 = new JButton("4");
		btn4.setForeground(new Color(255, 255, 255));
		btn4.setBackground(Color.DARK_GRAY);
		btn4.setFont(new Font("Arial", Font.BOLD, 21));
		btn4.addActionListener(new ActionListener() {
			public void actionPerformed(ActionEvent e)
			{
				String number=textField.getText()+btn4.getText();
				textField.setText(number);
			}
		});
		btn4.setBounds(8, 222, 60, 56);
		frame.getContentPane().add(btn4);
		
		final JButton btn5 = new JButton("5");
		btn5.addActionListener(new ActionListener() {
			public void actionPerformed(ActionEvent e) 
			{
				String number=textField.getText()+btn5.getText();
				textField.setText(number);
			}
		});
		btn5.setForeground(new Color(255, 255, 255));
		btn5.setBackground(Color.DARK_GRAY);
		btn5.setFont(new Font("Arial", Font.BOLD, 21));
		btn5.setBounds(80, 221, 60, 56);
		frame.getContentPane().add(btn5);
		
		final JButton btn6 = new JButton("6");
		btn6.addActionListener(new ActionListener() {
			public void actionPerformed(ActionEvent e) 
			{
				String number=textField.getText()+btn6.getText();
				textField.setText(number);
			}
		});
		btn6.setForeground(new Color(255, 255, 255));
		btn6.setBackground(Color.DARK_GRAY);
		btn6.setFont(new Font("Arial", Font.BOLD, 21));
		btn6.setBounds(150, 221, 60, 56);
		frame.getContentPane().add(btn6);
		
		final JButton btn7 = new JButton("7");
		btn7.addActionListener(new ActionListener() {
			public void actionPerformed(ActionEvent e) 
			{
				String number=textField.getText()+btn7.getText();
				textField.setText(number);
			}
		});
		btn7.setForeground(new Color(255, 255, 255));
		btn7.setBackground(Color.DARK_GRAY);
		btn7.setFont(new Font("Arial", Font.BOLD, 21));
		btn7.setBounds(8, 154, 60, 56);
		frame.getContentPane().add(btn7);
		
		final JButton btn8 = new JButton("8");
		btn8.addActionListener(new ActionListener() {
			public void actionPerformed(ActionEvent e)
			{
				String number=textField.getText()+btn8.getText();
				textField.setText(number);
			}
		});
		btn8.setForeground(new Color(255, 255, 255));
		btn8.setBackground(Color.DARK_GRAY);
		btn8.setFont(new Font("Arial", Font.BOLD, 21));
		btn8.setBounds(80, 154, 60, 56);
		frame.getContentPane().add(btn8);
		
		final JButton btn9 = new JButton("9");
		btn9.addActionListener(new ActionListener() {
			public void actionPerformed(ActionEvent e) 
			{
				String number=textField.getText()+btn9.getText();
				textField.setText(number);
			}
		});
		btn9.setForeground(new Color(255, 255, 255));
		btn9.setBackground(Color.DARK_GRAY);
		btn9.setFont(new Font("Arial", Font.BOLD, 21));
		btn9.setBounds(150, 154, 60, 56);
		frame.getContentPane().add(btn9);
		
		final JButton btnDiv = new JButton("/");
		btnDiv.addActionListener(new ActionListener() {
			public void actionPerformed(ActionEvent e)
			{
				first=Double.parseDouble(textField.getText());
				textField.setText("");
				operation="/";
			}
		});
		btnDiv.setForeground(Color.WHITE);
		btnDiv.setBackground(Color.GRAY);
		btnDiv.setFont(new Font("Arial", Font.BOLD, 21));
		btnDiv.setBounds(150, 85, 60, 56);
		frame.getContentPane().add(btnDiv);
		
		final JButton btnMul = new JButton("x");
		btnMul.addActionListener(new ActionListener() {
			public void actionPerformed(ActionEvent e) 
			{
				first=Double.parseDouble(textField.getText());
				textField.setText("");
				operation="*";
			}
		});
		btnMul.setForeground(new Color(255, 255, 255));
		btnMul.setBackground(Color.GRAY);
		btnMul.setFont(new Font("Arial", Font.BOLD, 21));
		btnMul.setBounds(220, 222, 60, 56);
		frame.getContentPane().add(btnMul);
		
		final JButton btnSub = new JButton("-");
		btnSub.addActionListener(new ActionListener() {
			public void actionPerformed(ActionEvent e)
			{
				first=Double.parseDouble(textField.getText());
				textField.setText("");
				operation="-";
			}
		});
		btnSub.setForeground(new Color(255, 255, 255));
		btnSub.setBackground(Color.GRAY);
		btnSub.setFont(new Font("Arial", Font.BOLD, 21));
		btnSub.setBounds(220, 154, 60, 56);
		frame.getContentPane().add(btnSub);
		
		final JButton btnPlus = new JButton("+");
		btnPlus.addActionListener(new ActionListener() {
			public void actionPerformed(ActionEvent e) 
			{
				first=Double.parseDouble(textField.getText());
				textField.setText("");
				operation="+";
			}
		});
		btnPlus.setForeground(Color.WHITE);
		btnPlus.setBackground(Color.GRAY);
		btnPlus.setFont(new Font("Arial", Font.BOLD, 21));
		btnPlus.setBounds(220, 85, 60, 56);
		frame.getContentPane().add(btnPlus);
		
		final JButton btnBack = new JButton("\uF0E7");
		btnBack.setForeground(new Color(255, 165, 0));
		btnBack.setBackground(Color.GRAY);
		btnBack.setFont(new Font("Wingdings", Font.PLAIN, 18));
		btnBack.addActionListener(new ActionListener() {
			public void actionPerformed(ActionEvent e)
			{
				String backSpace=null;
				if(textField.getText().length()>0)
				{
					StringBuilder str=new StringBuilder(textField.getText());
					str.deleteCharAt(textField.getText().length()-1);
					backSpace=str.toString();
					textField.setText(backSpace);
				}
			}
		});
		btnBack.setBounds(8, 85, 60, 56);
		frame.getContentPane().add(btnBack);
		
		final JButton btn0 = new JButton("0");
		btn0.addActionListener(new ActionListener() {
			public void actionPerformed(ActionEvent e)
			{
				String number=textField.getText()+btn0.getText();
				textField.setText(number);
			}
		});
		btn0.setForeground(new Color(255, 255, 255));
		btn0.setBackground(Color.DARK_GRAY);
		btn0.setFont(new Font("Arial", Font.BOLD, 21));
		btn0.setBounds(80, 356, 60, 56);
		frame.getContentPane().add(btn0);
		
		final JButton btn00 = new JButton("00");
		btn00.addActionListener(new ActionListener() {
			public void actionPerformed(ActionEvent e)
			{
				String number=textField.getText()+btn00.getText();
				textField.setText(number);
			}
		});
		btn00.setForeground(new Color(255, 255, 255));
		btn00.setBackground(Color.DARK_GRAY);
		btn00.setFont(new Font("Arial", Font.BOLD, 21));
		btn00.setBounds(150, 356, 60, 56);
		frame.getContentPane().add(btn00);
	}
}
