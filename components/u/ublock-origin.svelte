<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f99l4bb4c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f99l4bb4c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:ublock-origin" {...props}></Icon>
