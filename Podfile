platform :ios, '11.2'
source 'https://cdn.cocoapods.org/'
use_frameworks!

def common
	pod 'BinanceChain', :path => '.'
	# pod 'BinanceChain/Test', :path => '.'
	pod 'SwiftProtobuf', :inhibit_warnings => true
	pod 'Starscream', :inhibit_warnings => true
	pod 'HDWalletKit1', :inhibit_warnings => true
	pod 'CryptoSwift', :inhibit_warnings => true
end

target "Mobile" do
	platform :ios, '11.2'
	common
end
