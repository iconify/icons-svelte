<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e7byfuhup.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="e7byfuhup"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pencil:square-filled" {...props}></Icon>
