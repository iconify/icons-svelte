<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cavg_bvbw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="cavg_bvbw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:share-filled" {...props}></Icon>
