<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b8scwnjhi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b8scwnjhi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:timer-subtract-outline" {...props}></Icon>
