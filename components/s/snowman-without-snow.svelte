<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o6w6x0bgp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path clip-rule="evenodd" class="o6w6x0bgp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:snowman-without-snow" {...props}></Icon>
