<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yh5tb9bga.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yh5tb9bga"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:toggle-off-filled" {...props}></Icon>
