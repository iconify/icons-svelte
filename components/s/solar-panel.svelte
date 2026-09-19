<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ilw7d2bmv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="ilw7d2bmv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:solar-panel" {...props}></Icon>
