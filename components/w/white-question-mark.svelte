<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w6c5nib2b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="w6c5nib2b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:white-question-mark" {...props}></Icon>
