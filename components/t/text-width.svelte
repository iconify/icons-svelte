<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zgqlzrbgt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":24};
const content = `<path class="zgqlzrbgt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:text-width" {...props}></Icon>
