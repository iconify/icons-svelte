<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mdlpb_b-j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":24};
const content = `<path class="mdlpb_b-j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:vine" {...props}></Icon>
