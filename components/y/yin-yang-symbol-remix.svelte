<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/koyp5ltmq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="koyp5ltmq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:yin-yang-symbol-remix" {...props}></Icon>
