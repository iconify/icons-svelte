<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bc-l9fbmc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="bc-l9fbmc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:telephone" {...props}></Icon>
