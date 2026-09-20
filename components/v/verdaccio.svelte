<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w_xrss9fp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w_xrss9fp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:verdaccio" {...props}></Icon>
