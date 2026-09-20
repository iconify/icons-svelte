<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/je8ik9x9h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="je8ik9x9h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:xls-document-filled" {...props}></Icon>
