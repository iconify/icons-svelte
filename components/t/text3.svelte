<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iyl-rkbss.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iyl-rkbss"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:text3" {...props}></Icon>
