<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lkprxj80h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lkprxj80h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:sketch-outline" {...props}></Icon>
