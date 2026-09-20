<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t-mnshqpw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="t-mnshqpw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:station-wagon-under-key" {...props}></Icon>
