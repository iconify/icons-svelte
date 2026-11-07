<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kdob9slbu.css';
import '../../css/v/v3h9yd14e.css';
import '../../css/h/ht8rgl0oc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kdob9slbu"/><path class="v3h9yd14e"/><path class="ht8rgl0oc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:to-pip-bold-duotone" {...props}></Icon>
