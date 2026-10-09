<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jz02pm04a.css';
import '../../css/u/ucu3b4dxx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="jz02pm04a"/><path class="ucu3b4dxx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:sea-level-rise-48" {...props}></Icon>
