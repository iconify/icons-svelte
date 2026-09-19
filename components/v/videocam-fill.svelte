<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dsx7mlbfl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="dsx7mlbfl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:videocam-fill" {...props}></Icon>
