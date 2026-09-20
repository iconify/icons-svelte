<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vsne3db-f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="vsne3db-f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:superscript" {...props}></Icon>
