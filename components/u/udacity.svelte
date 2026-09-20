<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nj930lbty.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nj930lbty"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:udacity" {...props}></Icon>
