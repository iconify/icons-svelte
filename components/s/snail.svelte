<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/scjzlfbsp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="scjzlfbsp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:snail" {...props}></Icon>
