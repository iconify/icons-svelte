<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lld64mb1j.css';
import '../../css/y/yno7aib_e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="lld64mb1j"/><path class="yno7aib_e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:shield-user-48" {...props}></Icon>
