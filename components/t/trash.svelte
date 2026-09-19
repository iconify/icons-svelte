<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p92x1l1zg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="p92x1l1zg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:trash" {...props}></Icon>
