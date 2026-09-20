<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fkc--sb8t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="fkc--sb8t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:skull" {...props}></Icon>
