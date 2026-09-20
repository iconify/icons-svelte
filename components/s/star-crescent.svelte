<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/btvzwg_0d.css';
import '../../css/f/f7-f7bvjr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="btvzwg_0d"/><path class="f7-f7bvjr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:star-crescent" {...props}></Icon>
