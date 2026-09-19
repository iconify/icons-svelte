<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lyo5l_bak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lyo5l_bak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:stylus-orb" {...props}></Icon>
