<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hd1dacc8z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hd1dacc8z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:sponge" {...props}></Icon>
