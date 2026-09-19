<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d1n2isbof.css';
import '../../css/m/mn36lt97b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d1n2isbof"/><path class="mn36lt97b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:self-care" {...props}></Icon>
