<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yqhh8rxsc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yqhh8rxsc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:square-split-horizontal" {...props}></Icon>
