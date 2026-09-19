<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u_01jj14b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u_01jj14b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:zoom-out-thin" {...props}></Icon>
