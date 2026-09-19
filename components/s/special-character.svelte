<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kgvxtg2bf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kgvxtg2bf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gridicons:special-character" {...props}></Icon>
