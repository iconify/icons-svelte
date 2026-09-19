<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/chjylrhmo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="chjylrhmo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:wrapped-gift" {...props}></Icon>
