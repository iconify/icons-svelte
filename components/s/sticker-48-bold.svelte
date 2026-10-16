<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u_pz37b4w.css';
import '../../css/u/u-jkgcbqr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="u_pz37b4w"/><path class="u-jkgcbqr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:sticker-48-bold" {...props}></Icon>
