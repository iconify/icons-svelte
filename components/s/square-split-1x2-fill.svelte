<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rdmtibc3m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="rdmtibc3m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:square-split-1x2-fill" {...props}></Icon>
