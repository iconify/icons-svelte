<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n9dd0e63q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n9dd0e63q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:scale-balance" {...props}></Icon>
