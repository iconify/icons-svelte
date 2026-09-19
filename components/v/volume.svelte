<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zv32racfe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zv32racfe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:volume" {...props}></Icon>
