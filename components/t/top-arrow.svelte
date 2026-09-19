<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gbgiu0boz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="gbgiu0boz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:top-arrow" {...props}></Icon>
