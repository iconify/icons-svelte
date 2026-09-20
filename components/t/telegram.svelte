<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d3wm8ghmk.css';
import '../../css/c/c6ogy1b5a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d3wm8ghmk"/><path class="c6ogy1b5a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:telegram" {...props}></Icon>
