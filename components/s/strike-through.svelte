<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iyuep_bqx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iyuep_bqx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:strike-through" {...props}></Icon>
