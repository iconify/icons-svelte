<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kmknqabws.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="kmknqabws"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:small-airplane" {...props}></Icon>
