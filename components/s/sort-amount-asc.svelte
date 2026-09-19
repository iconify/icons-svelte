<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g7ja_s0el.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="g7ja_s0el"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:sort-amount-asc" {...props}></Icon>
