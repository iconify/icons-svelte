<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i6-zcrkji.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i6-zcrkji"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:sorting-05" {...props}></Icon>
