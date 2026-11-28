<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rry400bso.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rry400bso"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:salad-heart" {...props}></Icon>
