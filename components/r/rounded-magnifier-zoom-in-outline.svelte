<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g7g4d_bmg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g7g4d_bmg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:rounded-magnifier-zoom-in-outline" {...props}></Icon>
