<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r10aijb9l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="r10aijb9l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:share" {...props}></Icon>
