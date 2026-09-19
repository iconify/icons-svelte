<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ksr012bdk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ksr012bdk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:woman-supervillain" {...props}></Icon>
