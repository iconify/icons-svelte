<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i1abfbc-g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":384};
const content = `<path class="i1abfbc-g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:time-countdown" {...props}></Icon>
