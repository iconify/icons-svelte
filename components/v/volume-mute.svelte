<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mttzz5vbg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mttzz5vbg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:volume-mute" {...props}></Icon>
