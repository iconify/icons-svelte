<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o_1m5nb6h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="o_1m5nb6h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:spellcheck" {...props}></Icon>
