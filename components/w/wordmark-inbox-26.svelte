<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j8yrp8bih.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":26};
const content = `<path class="j8yrp8bih"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:wordmark-inbox-26" {...props}></Icon>
