<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ikd4kd-ww.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="ikd4kd-ww"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:snowplow" {...props}></Icon>
