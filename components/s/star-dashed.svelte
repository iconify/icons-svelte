<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kh-1a_bae.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kh-1a_bae"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:star-dashed" {...props}></Icon>
