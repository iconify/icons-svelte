<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hytede6zc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hytede6zc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:shoe" {...props}></Icon>
