<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lcx_ksbcd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lcx_ksbcd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:tablets" {...props}></Icon>
