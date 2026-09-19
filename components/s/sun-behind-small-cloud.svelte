<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d6_kfdbka.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="d6_kfdbka"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:sun-behind-small-cloud" {...props}></Icon>
