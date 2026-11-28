<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cnva-97fi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cnva-97fi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:thumbs-up" {...props}></Icon>
