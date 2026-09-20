<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/asqh4ebny.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="asqh4ebny"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:seagate" {...props}></Icon>
