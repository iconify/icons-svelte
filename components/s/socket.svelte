<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m2h16x32u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m2h16x32u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:socket" {...props}></Icon>
