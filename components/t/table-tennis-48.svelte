<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ytknsibzh.css';
import '../../css/v/vr1h12b6u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ytknsibzh"/><path class="vr1h12b6u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:table-tennis-48" {...props}></Icon>
