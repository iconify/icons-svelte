<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p52rodbso.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="p52rodbso"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:wheel" {...props}></Icon>
