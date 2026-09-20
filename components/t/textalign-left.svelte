<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xu1uclb9m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xu1uclb9m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:textalign-left" {...props}></Icon>
