<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d06squwrc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="d06squwrc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:stats" {...props}></Icon>
