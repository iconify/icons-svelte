<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tq7dhvbqx.css';
import '../../css/p/pf1wtprxb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tq7dhvbqx"/><path class="pf1wtprxb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:shipit" {...props}></Icon>
