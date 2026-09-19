<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qacjvq_4i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qacjvq_4i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:unity" {...props}></Icon>
