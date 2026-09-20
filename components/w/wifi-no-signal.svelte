<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l3dtm-mrc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="l3dtm-mrc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:wifi-no-signal" {...props}></Icon>
