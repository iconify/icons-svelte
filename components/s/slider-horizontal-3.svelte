<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jwlopty2a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="jwlopty2a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:slider-horizontal-3" {...props}></Icon>
