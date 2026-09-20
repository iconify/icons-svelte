<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l-qq7fbyk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="l-qq7fbyk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="quill:stack-alt" {...props}></Icon>
