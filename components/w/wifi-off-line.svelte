<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/skahjs8zz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="skahjs8zz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:wifi-off-line" {...props}></Icon>
