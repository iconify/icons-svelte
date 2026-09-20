<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p6spicclu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p6spicclu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:sort-a-z" {...props}></Icon>
