<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pu8nhg2df.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="pu8nhg2df"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:thunderbolt-fill" {...props}></Icon>
