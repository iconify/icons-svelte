<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zbm3ckrdg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zbm3ckrdg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:ticket-star-bold" {...props}></Icon>
