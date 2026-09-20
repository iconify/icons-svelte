<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dtnj1pydm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dtnj1pydm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:vectors-anchor-rectangle-bold" {...props}></Icon>
