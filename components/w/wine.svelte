<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/peommn6jl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="peommn6jl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:wine" {...props}></Icon>
