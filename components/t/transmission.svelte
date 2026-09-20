<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cp5eb4clg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cp5eb4clg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:transmission" {...props}></Icon>
