<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rcp1jpslu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="rcp1jpslu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:sunset" {...props}></Icon>
