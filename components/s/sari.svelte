<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v_4kopb1n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="v_4kopb1n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:sari" {...props}></Icon>
