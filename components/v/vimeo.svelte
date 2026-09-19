<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nwio0m8eo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="nwio0m8eo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:vimeo" {...props}></Icon>
