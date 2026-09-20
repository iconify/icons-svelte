<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uzow1dvyv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uzow1dvyv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:send-twice-square-bold" {...props}></Icon>
