<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jasc9ibwg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jasc9ibwg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:square-play" {...props}></Icon>
