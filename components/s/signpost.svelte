<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pm5ehfbqs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="pm5ehfbqs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:signpost" {...props}></Icon>
