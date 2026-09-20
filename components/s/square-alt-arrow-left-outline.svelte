<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r0bt8abzo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r0bt8abzo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:square-alt-arrow-left-outline" {...props}></Icon>
