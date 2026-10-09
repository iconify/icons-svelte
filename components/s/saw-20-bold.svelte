<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jj41r93vd.css';
import '../../css/n/nfvrmwb9e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="jj41r93vd"/><path class="nfvrmwb9e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:saw-20-bold" {...props}></Icon>
