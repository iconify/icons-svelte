<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lob7ambba.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lob7ambba"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:yugabytedb-light" {...props}></Icon>
