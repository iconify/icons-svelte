<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eh1r_abuc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="eh1r_abuc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:two-hearts" {...props}></Icon>
