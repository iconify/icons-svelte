<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ub35knbuk.css';
import '../../css/d/d_qmu7ifq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ub35knbuk"/><path class="d_qmu7ifq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:teer" {...props}></Icon>
