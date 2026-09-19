<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y3l9webvv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y3l9webvv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mono-icons:select" {...props}></Icon>
