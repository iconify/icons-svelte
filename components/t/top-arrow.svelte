<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r9xqzn69c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="r9xqzn69c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:top-arrow" {...props}></Icon>
