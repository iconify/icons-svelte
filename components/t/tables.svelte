<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k202uvbjw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1664,"height":1664};
const content = `<path class="k202uvbjw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vs:tables" {...props}></Icon>
