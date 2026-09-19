<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ngr-7c-ny.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ngr-7c-ny"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:wikipedia" {...props}></Icon>
