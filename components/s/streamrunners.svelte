<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pc49i48eh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pc49i48eh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:streamrunners" {...props}></Icon>
