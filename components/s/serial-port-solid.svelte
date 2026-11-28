<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hu2k_gbzh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hu2k_gbzh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:serial-port-solid" {...props}></Icon>
