<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mq6mer8bc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="mq6mer8bc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:square-split-2x2" {...props}></Icon>
