<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/onycniudx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="onycniudx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:text-document-alt-outline" {...props}></Icon>
