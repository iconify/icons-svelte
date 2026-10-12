<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wnk2uvdxf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wnk2uvdxf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:square-dimensions-filled" {...props}></Icon>
