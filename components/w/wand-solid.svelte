<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rgix3bcvw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rgix3bcvw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:wand-solid" {...props}></Icon>
