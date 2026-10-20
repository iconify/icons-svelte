<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mqwetvawk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="mqwetvawk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:sparkle-48" {...props}></Icon>
