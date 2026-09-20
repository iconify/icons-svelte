<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kv_3wkq1r.css';
import '../../css/w/wisf880rp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kv_3wkq1r"/><path class="wisf880rp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:zerotier" {...props}></Icon>
