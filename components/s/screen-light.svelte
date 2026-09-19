<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/unwk3lcee.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="unwk3lcee"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:screen-light" {...props}></Icon>
