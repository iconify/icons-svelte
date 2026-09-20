<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wun8kyb2z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="wun8kyb2z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:rtl" {...props}></Icon>
