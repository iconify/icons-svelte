<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jjsxf6bra.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jjsxf6bra"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:unsplash" {...props}></Icon>
