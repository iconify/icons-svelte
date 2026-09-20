<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c2cj950ou.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c2cj950ou"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:xo" {...props}></Icon>
