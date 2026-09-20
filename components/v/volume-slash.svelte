<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ale99obtf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ale99obtf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:volume-slash" {...props}></Icon>
