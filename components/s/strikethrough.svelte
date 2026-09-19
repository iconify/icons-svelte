<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/emvqg1cza.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="emvqg1cza"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:strikethrough" {...props}></Icon>
