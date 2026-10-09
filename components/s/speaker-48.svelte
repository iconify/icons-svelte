<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/batmvgb8l.css';
import '../../css/k/ks20pegmu.css';
import '../../css/d/dczvvtbjx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="batmvgb8l"/><path class="ks20pegmu"/><path class="dczvvtbjx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:speaker-48" {...props}></Icon>
