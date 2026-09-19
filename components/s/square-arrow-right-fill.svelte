<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/blh-a7_ck.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="blh-a7_ck"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:square-arrow-right-fill" {...props}></Icon>
