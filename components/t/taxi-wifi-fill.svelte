<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g4c_pcbxg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g4c_pcbxg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:taxi-wifi-fill" {...props}></Icon>
