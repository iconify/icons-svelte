<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e4h2p03zn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":42,"height":42};
const content = `<path class="e4h2p03zn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="topcoat:user" {...props}></Icon>
