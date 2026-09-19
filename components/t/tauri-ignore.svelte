<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cvcq89ble.css';
import '../../css/o/oa964uw4k.css';
import '../../css/q/q8ppmua1p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="cvcq89ble"><path class="oa964uw4k"/><path class="q8ppmua1p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:tauri-ignore" {...props}></Icon>
