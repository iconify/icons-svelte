<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ons7wnazk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":462,"height":698};
const content = `<path class="ons7wnazk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:sort" {...props}></Icon>
