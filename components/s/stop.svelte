<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c2x6fgl2v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c2x6fgl2v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:stop" {...props}></Icon>
