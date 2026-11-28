<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jpoln0yba.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jpoln0yba"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:shower" {...props}></Icon>
