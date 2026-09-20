<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kgq2-68dl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kgq2-68dl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mi:sort" {...props}></Icon>
