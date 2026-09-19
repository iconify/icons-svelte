<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/duy9jjbmx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1025};
const content = `<path class="duy9jjbmx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:software" {...props}></Icon>
