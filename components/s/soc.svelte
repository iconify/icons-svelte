<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sq2_p6b2r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="sq2_p6b2r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:soc" {...props}></Icon>
