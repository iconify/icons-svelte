<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e1z02kbki.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="e1z02kbki"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:sos" {...props}></Icon>
