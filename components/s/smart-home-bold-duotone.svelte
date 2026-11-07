<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g23epvw1o.css';
import '../../css/z/zph51jbiz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g23epvw1o"/><path clip-rule="evenodd" class="zph51jbiz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:smart-home-bold-duotone" {...props}></Icon>
