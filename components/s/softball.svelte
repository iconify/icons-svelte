<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/leg0v_b6k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="leg0v_b6k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:softball" {...props}></Icon>
