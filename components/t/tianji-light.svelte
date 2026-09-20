<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p9hnn2kgg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="p9hnn2kgg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:tianji-light" {...props}></Icon>
