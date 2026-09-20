<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dvmdrtmdd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="dvmdrtmdd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:slaughterhouse" {...props}></Icon>
