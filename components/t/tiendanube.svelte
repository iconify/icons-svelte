<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q22_55b6f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="q22_55b6f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nimbus:tiendanube" {...props}></Icon>
