<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zzef9p_tp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zzef9p_tp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:square-i" {...props}></Icon>
