<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/llzg3ib9q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="llzg3ib9q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:sort-ascending-fill" {...props}></Icon>
