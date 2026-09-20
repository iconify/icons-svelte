<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jkkjs4bjp.css';
import '../../css/u/uwu_w82bn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jkkjs4bjp"/><path class="uwu_w82bn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:swftc" {...props}></Icon>
