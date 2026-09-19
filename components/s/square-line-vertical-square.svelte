<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gnv5u_5dq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="gnv5u_5dq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:square-line-vertical-square" {...props}></Icon>
