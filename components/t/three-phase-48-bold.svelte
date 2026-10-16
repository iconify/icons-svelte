<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zcunuwblp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="zcunuwblp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:three-phase-48-bold" {...props}></Icon>
