<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y03uq8b5g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y03uq8b5g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:tor-browser" {...props}></Icon>
