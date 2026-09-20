<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mw1fx7b1y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mw1fx7b1y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:scilab" {...props}></Icon>
