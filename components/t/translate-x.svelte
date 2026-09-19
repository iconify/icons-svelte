<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s6s918ojl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="s6s918ojl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:translate-x" {...props}></Icon>
