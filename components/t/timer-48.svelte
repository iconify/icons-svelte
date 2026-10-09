<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cohfbvw_w.css';
import '../../css/w/ws9mn_3ua.css';
import '../../css/x/xkkhb5coq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="cohfbvw_w"/><path class="ws9mn_3ua"/><path class="xkkhb5coq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:timer-48" {...props}></Icon>
