<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ymiz41-qh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ymiz41-qh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:xml" {...props}></Icon>
