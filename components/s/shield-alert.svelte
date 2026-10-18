<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d1p7v_xfn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d1p7v_xfn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:shield-alert" {...props}></Icon>
