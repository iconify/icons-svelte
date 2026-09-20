<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kbi7zsbjh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kbi7zsbjh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-cyber:usb" {...props}></Icon>
