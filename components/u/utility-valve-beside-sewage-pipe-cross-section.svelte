<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/anu_i_-lk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="anu_i_-lk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:utility-valve-beside-sewage-pipe-cross-section" {...props}></Icon>
