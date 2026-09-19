<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cyoqdrbia.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="cyoqdrbia"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:step-o" {...props}></Icon>
