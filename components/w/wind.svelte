<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bgh8pwb1j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bgh8pwb1j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:wind" {...props}></Icon>
