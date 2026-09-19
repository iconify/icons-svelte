<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pjacrgb5d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="pjacrgb5d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:type-h2" {...props}></Icon>
