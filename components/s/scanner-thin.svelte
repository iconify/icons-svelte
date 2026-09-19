<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c6wc6fb0p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c6wc6fb0p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:scanner-thin" {...props}></Icon>
