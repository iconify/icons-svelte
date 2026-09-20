<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sufv57bfh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sufv57bfh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:smithery" {...props}></Icon>
