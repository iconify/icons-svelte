<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x_kk64s-x.css';
import '../../css/p/p_p4lxbry.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="x_kk64s-x"/><path class="p_p4lxbry"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:spotify-for-creators" {...props}></Icon>
