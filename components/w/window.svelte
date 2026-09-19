<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pq2h9qb2m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pq2h9qb2m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:window" {...props}></Icon>
