<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t8qpreaht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="t8qpreaht"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:rssrise-light" {...props}></Icon>
