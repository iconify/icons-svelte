<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hb907bc8d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hb907bc8d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:telegram" {...props}></Icon>
