<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kq38d_g_r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kq38d_g_r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:whistle-outline" {...props}></Icon>
