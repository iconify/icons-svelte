<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zen2agbyu.css';
import '../../css/h/hb4ovmb-c.css';
import '../../css/r/rbbtambdl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="zen2agbyu"/><path class="hb4ovmb-c"/><path class="rbbtambdl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:steering-wheel-48" {...props}></Icon>
