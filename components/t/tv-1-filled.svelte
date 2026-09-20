<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fvh306brv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fvh306brv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:tv-1-filled" {...props}></Icon>
