<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/njnebub6m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="njnebub6m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:xmcc" {...props}></Icon>
