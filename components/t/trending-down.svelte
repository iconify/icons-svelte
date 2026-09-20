<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u3qet9wal.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="u3qet9wal"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wordpress:trending-down" {...props}></Icon>
