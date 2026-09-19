<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hwaudvbpi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hwaudvbpi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="academicons:semantic-scholar" {...props}></Icon>
