<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m0vo_rj-b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m0vo_rj-b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:sun-snow" {...props}></Icon>
