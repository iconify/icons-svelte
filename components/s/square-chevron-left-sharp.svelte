<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fjs7sj05i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fjs7sj05i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:square-chevron-left-sharp" {...props}></Icon>
