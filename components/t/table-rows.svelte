<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jv1vpq53t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jv1vpq53t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:table-rows" {...props}></Icon>
