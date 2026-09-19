<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ike5_5lfu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="ike5_5lfu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:shield" {...props}></Icon>
