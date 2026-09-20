<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wds76yb_c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wds76yb_c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:yugabytedb-light" {...props}></Icon>
