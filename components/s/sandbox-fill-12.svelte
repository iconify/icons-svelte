<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ua9bmhbea.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="ua9bmhbea"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:sandbox-fill-12" {...props}></Icon>
