<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/csd0tik1g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="csd0tik1g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:webflow" {...props}></Icon>
