<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vv212v18f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":24};
const content = `<path class="vv212v18f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:wind" {...props}></Icon>
