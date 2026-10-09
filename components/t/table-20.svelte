<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wetq5b_1u.css';
import '../../css/d/d1j6p8b_k.css';
import '../../css/q/qqk1d6grf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="wetq5b_1u"/><path class="d1j6p8b_k"/><path class="qqk1d6grf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:table-20" {...props}></Icon>
