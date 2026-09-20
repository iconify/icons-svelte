<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mmt0j8b9a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="mmt0j8b9a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:viewpoint-15" {...props}></Icon>
