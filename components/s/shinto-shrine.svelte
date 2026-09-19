<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uor91wbfu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="uor91wbfu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:shinto-shrine" {...props}></Icon>
