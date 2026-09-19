<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wap2xvans.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="wap2xvans"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:sprint" {...props}></Icon>
