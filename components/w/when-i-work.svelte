<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dq6hfab4z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dq6hfab4z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:when-i-work" {...props}></Icon>
