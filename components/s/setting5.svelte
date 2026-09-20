<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mn7kabcvh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mn7kabcvh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:setting5" {...props}></Icon>
