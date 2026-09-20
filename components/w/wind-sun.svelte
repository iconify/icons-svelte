<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zpc1zdbtb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zpc1zdbtb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:wind-sun" {...props}></Icon>
