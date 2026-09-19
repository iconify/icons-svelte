<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iuu31hbeu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iuu31hbeu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:torch" {...props}></Icon>
