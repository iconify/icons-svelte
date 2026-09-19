<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mc8sz1b-a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="mc8sz1b-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:white-exclamation-mark" {...props}></Icon>
