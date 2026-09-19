<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fc_3cbc1b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="fc_3cbc1b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:toothbrush" {...props}></Icon>
