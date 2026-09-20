<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oomvw6b6h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oomvw6b6h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:wikipedia" {...props}></Icon>
