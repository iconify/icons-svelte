<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z1l3lq7gm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z1l3lq7gm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:xbox-controller-view" {...props}></Icon>
