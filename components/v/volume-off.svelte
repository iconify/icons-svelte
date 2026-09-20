<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gyxfesbsu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gyxfesbsu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:volume-off" {...props}></Icon>
