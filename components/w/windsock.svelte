<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jft04mbyf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jft04mbyf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:windsock" {...props}></Icon>
