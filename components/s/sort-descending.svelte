<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i4cfat-tq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i4cfat-tq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:sort-descending" {...props}></Icon>
