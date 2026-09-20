<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wmleipb7g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wmleipb7g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:square-sharp" {...props}></Icon>
