<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lt9n4ob1n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lt9n4ob1n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:stroke-right" {...props}></Icon>
