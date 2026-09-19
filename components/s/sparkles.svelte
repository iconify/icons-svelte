<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ir_1hvbbr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ir_1hvbbr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:sparkles" {...props}></Icon>
