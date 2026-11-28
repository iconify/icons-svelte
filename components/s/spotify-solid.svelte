<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pu0s4ebai.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pu0s4ebai"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:spotify-solid" {...props}></Icon>
