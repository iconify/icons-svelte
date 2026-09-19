<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i95u-8bjy.css';
import '../../css/d/dxyzwm2nj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="i95u-8bjy"/><path class="dxyzwm2nj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:volume-unmuted-fill-16" {...props}></Icon>
