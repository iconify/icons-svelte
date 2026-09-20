<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/adfb9-j1g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="adfb9-j1g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:sourceforge" {...props}></Icon>
