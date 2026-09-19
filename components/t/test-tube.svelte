<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/anx0eybut.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="anx0eybut"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:test-tube" {...props}></Icon>
