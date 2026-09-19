<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zzc_2nz_m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zzc_2nz_m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:squircle" {...props}></Icon>
