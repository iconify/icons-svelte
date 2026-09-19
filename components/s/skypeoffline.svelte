<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jbtuw1bio.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="jbtuw1bio"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:skypeoffline" {...props}></Icon>
