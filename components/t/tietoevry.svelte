<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j9a06w5xt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j9a06w5xt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:tietoevry" {...props}></Icon>
