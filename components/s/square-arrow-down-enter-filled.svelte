<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g6pd55bue.css';
import '../../css/j/j7n6h9bec.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g6pd55bue"/><path class="j7n6h9bec"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:square-arrow-down-enter-filled" {...props}></Icon>
