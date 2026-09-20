<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b8rbiiblu.css';
import '../../css/w/w_gkkwbts.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b8rbiiblu"/><path class="w_gkkwbts"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:sshwifty-light" {...props}></Icon>
