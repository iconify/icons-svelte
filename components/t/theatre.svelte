<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vlxc-_bbu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vlxc-_bbu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:theatre" {...props}></Icon>
