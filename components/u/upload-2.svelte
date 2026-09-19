<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nc2-ddicz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="nc2-ddicz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:upload-2" {...props}></Icon>
