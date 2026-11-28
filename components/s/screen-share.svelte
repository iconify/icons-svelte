<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bjjzh5ydp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bjjzh5ydp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:screen-share" {...props}></Icon>
