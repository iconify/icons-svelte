<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tl8uu2nzg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tl8uu2nzg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:virgo-fill" {...props}></Icon>
