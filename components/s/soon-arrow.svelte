<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ijtgd6bbq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ijtgd6bbq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:soon-arrow" {...props}></Icon>
