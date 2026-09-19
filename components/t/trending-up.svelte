<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/skpvnv86r.css';
import '../../css/l/lrldwibcs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="skpvnv86r"/><path class="lrldwibcs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:trending-up" {...props}></Icon>
