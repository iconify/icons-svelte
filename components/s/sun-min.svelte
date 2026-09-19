<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/by8gydbjt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="by8gydbjt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:sun-min" {...props}></Icon>
