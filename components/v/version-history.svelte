<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z521863aw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="z521863aw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:version-history" {...props}></Icon>
