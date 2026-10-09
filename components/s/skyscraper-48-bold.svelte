<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g_3xo-zcn.css';
import '../../css/f/fy8hrfkoj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="g_3xo-zcn"/><path class="fy8hrfkoj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:skyscraper-48-bold" {...props}></Icon>
