<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w2i4q55vh.css';
import '../../css/k/kqqve2g3f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w2i4q55vh"/><path class="kqqve2g3f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:sort-amount-down-alt" {...props}></Icon>
