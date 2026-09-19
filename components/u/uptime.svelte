<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oqcx_7bje.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="oqcx_7bje"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:uptime" {...props}></Icon>
