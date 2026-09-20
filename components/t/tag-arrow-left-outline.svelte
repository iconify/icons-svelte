<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lmmqdfyrk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lmmqdfyrk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:tag-arrow-left-outline" {...props}></Icon>
