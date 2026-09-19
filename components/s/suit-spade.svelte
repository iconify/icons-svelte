<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cmr2z5nok.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="cmr2z5nok"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:suit-spade" {...props}></Icon>
