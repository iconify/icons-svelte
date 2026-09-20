<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xses9xq_t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xses9xq_t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:visual-db" {...props}></Icon>
