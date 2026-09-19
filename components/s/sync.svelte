<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hzwag_bhx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hzwag_bhx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:sync" {...props}></Icon>
