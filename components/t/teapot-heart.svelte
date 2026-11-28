<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ou2178jow.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ou2178jow"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:teapot-heart" {...props}></Icon>
