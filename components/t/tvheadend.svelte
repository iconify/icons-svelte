<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bd94q1l9h.css';
import '../../css/p/p1u6d8a7v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bd94q1l9h"/><path class="p1u6d8a7v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:tvheadend" {...props}></Icon>
