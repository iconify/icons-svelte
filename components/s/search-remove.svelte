<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/upo1axb2n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="upo1axb2n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:search-remove" {...props}></Icon>
