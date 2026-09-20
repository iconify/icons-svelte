<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u8ktb-bmq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="u8ktb-bmq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-line-icons:size-fullscreen" {...props}></Icon>
