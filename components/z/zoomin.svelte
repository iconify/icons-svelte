<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/csah_sx9w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="csah_sx9w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:zoomin" {...props}></Icon>
