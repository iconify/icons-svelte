<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lrbukw_4s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lrbukw_4s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:trophy" {...props}></Icon>
