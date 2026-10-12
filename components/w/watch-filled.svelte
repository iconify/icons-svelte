<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/ddqahgmbx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ddqahgmbx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:watch-filled" {...props}></Icon>
