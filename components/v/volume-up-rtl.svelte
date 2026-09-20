<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f8f6_-atn.css';
import '../../css/b/b_7qycc3l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="f8f6_-atn"/><path class="b_7qycc3l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:volume-up-rtl" {...props}></Icon>
