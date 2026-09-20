<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ogqr599um.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ogqr599um"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:yunohost" {...props}></Icon>
