<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dz0grn9tw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dz0grn9tw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:weblate-light" {...props}></Icon>
