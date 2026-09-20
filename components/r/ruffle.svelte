<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bn9l47b1z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bn9l47b1z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:ruffle" {...props}></Icon>
