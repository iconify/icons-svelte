<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vil-2abad.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vil-2abad"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:tree-palm-two-tone" {...props}></Icon>
