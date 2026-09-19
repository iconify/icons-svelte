<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b67w6_c5v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="b67w6_c5v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:snap" {...props}></Icon>
