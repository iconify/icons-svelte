<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ih1h7z2gg.css';
import '../../css/l/l_7m7z2gc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ih1h7z2gg"/><path class="l_7m7z2gc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:volume-on-fill-20" {...props}></Icon>
