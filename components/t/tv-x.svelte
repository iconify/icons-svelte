<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/arh5dy41k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="arh5dy41k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:tv-x" {...props}></Icon>
