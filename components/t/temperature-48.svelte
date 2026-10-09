<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lg26btbri.css';
import '../../css/i/iasbg5lvo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="lg26btbri"/><path class="iasbg5lvo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:temperature-48" {...props}></Icon>
