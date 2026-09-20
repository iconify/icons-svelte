<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xu8qm5b8x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xu8qm5b8x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:tooljet-light" {...props}></Icon>
