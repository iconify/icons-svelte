<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hd-jtvbfj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hd-jtvbfj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:trpc" {...props}></Icon>
