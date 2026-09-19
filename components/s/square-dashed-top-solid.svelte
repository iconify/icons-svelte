<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l2nrntb2j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l2nrntb2j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:square-dashed-top-solid" {...props}></Icon>
