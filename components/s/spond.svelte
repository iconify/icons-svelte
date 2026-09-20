<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f5l_xac5z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f5l_xac5z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:spond" {...props}></Icon>
