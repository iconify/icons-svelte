<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/buosklrvg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="buosklrvg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:terminal-solid" {...props}></Icon>
