<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fmp5x0bgg.css';
import '../../css/k/kqqve2g3f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fmp5x0bgg"/><path class="kqqve2g3f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:sort-amount-up-alt" {...props}></Icon>
