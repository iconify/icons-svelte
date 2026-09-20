<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hxp47pdsx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hxp47pdsx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:ticket" {...props}></Icon>
