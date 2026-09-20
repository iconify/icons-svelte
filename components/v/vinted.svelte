<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rry_6hbgi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rry_6hbgi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:vinted" {...props}></Icon>
