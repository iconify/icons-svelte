<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bxytyntgb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="bxytyntgb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:square-grid-2x2" {...props}></Icon>
