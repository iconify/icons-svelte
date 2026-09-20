<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f0zn-7b3r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f0zn-7b3r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:zcool" {...props}></Icon>
