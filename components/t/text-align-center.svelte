<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yul4kcybh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yul4kcybh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:text-align-center" {...props}></Icon>
