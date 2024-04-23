package com.example.jenkinsjobapplication;

import jakarta.annotation.PostConstruct;
import org.apache.juli.logging.LogFactory;
import org.springframework.boot.SpringApplication;
import org.springframework.boot.autoconfigure.SpringBootApplication;

import java.util.logging.Logger;

@SpringBootApplication
public class JenkinsJobApplication   {

	//public static Logger logger = (Logger) LogFactory.getLog(JenkinsJobApplication.class);

	@PostConstruct
	 public void init(){
		System.out.println(" Dev Environment ");
	 }
	public static void main(String[] args) {
		SpringApplication.run(JenkinsJobApplication.class, args);
	}

}
