<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z48zn0bsm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z48zn0bsm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:signpost-line" {...props}></Icon>
