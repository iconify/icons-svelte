<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sf4_o-boe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="sf4_o-boe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:square-fill-on-circle-fill" {...props}></Icon>
