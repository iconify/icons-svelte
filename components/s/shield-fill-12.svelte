<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a-idg35bc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="a-idg35bc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:shield-fill-12" {...props}></Icon>
