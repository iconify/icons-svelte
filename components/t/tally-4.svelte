<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dck9ixbrm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dck9ixbrm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:tally-4" {...props}></Icon>
