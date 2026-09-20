<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o-0g1m3_t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o-0g1m3_t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:subtraction-1" {...props}></Icon>
