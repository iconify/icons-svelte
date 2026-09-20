<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/juuloylmq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="juuloylmq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:scissors-bold" {...props}></Icon>
