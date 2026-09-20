<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rm3tpvt0r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rm3tpvt0r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:scan-helper" {...props}></Icon>
