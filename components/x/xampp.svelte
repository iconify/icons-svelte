<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lt4ma9bdp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lt4ma9bdp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:xampp" {...props}></Icon>
