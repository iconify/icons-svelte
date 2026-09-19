<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gu2_l9r9r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="gu2_l9r9r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:sort-down" {...props}></Icon>
