<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w2b_8yxjd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="w2b_8yxjd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:xmark" {...props}></Icon>
