<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oy_9tw95l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oy_9tw95l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:vuejs-line" {...props}></Icon>
