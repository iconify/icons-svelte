<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jspq0yv0r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="jspq0yv0r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:zsh-wordmark" {...props}></Icon>
