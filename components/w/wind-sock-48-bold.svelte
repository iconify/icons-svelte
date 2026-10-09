<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l359dqins.css';
import '../../css/d/dcw38u4hx.css';
import '../../css/f/f7u3lacne.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="l359dqins"/><path class="dcw38u4hx"/><path class="f7u3lacne"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:wind-sock-48-bold" {...props}></Icon>
