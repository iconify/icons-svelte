<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u6v803isl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u6v803isl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:tor-project" {...props}></Icon>
