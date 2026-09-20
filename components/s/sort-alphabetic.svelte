<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/csvt9dbkc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="csvt9dbkc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:sort-alphabetic" {...props}></Icon>
