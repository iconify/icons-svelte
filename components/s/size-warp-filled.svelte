<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cv21hpb-x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cv21hpb-x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:size-warp-filled" {...props}></Icon>
