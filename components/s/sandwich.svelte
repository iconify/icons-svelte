<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/enich5jvk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="enich5jvk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:sandwich" {...props}></Icon>
