<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r9y3__bbk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r9y3__bbk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:service-fill" {...props}></Icon>
