<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t8mx5jbcs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="t8mx5jbcs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:user-check-48-bold" {...props}></Icon>
