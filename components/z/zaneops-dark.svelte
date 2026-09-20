<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vtvc137bm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vtvc137bm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:zaneops-dark" {...props}></Icon>
