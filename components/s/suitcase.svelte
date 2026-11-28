<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dbxg65bzn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dbxg65bzn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:suitcase" {...props}></Icon>
