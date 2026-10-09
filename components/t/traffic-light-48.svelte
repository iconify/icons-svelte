<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hc9t8fp5n.css';
import '../../css/n/nl5mucbfu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="hc9t8fp5n"/><path class="nl5mucbfu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:traffic-light-48" {...props}></Icon>
