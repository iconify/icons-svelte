<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/edhu5n-ej.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="edhu5n-ej"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="quill:snooze-month" {...props}></Icon>
