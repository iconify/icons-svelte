<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oo1cg3arb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oo1cg3arb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:taxi-check" {...props}></Icon>
