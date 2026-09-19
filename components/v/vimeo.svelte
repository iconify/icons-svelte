<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cxys4rbxx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":28,"height":24};
const content = `<path class="cxys4rbxx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:vimeo" {...props}></Icon>
