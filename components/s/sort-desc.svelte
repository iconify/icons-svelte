<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qwjtdfb1l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qwjtdfb1l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:sort-desc" {...props}></Icon>
