<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mjz9o4bol.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mjz9o4bol"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:story" {...props}></Icon>
