<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ohg2owb1n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ohg2owb1n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:sling2x-outline" {...props}></Icon>
