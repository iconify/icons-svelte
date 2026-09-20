<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/attlt2bak.css';
import '../../css/w/w5pegf6wk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="attlt2bak"/><path class="w5pegf6wk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:vending-newspaper" {...props}></Icon>
