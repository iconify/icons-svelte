<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fe_m16lxw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fe_m16lxw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:scroll-text" {...props}></Icon>
