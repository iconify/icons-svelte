<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bsl6fiboz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bsl6fiboz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:solar-energy-alt-filled" {...props}></Icon>
