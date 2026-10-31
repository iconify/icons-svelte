<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gvl4myhbs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gvl4myhbs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:sprout-fill-round" {...props}></Icon>
