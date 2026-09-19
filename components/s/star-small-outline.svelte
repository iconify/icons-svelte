<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dwg3kp-2f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="dwg3kp-2f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:star-small-outline" {...props}></Icon>
