<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n8ibeob9s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":489,"height":512};
const content = `<path class="n8ibeob9s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:sophia" {...props}></Icon>
