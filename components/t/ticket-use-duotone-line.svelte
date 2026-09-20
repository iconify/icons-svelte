<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kwb0gcbpy.css';
import '../../css/o/o02y6724p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kwb0gcbpy"/><path class="o02y6724p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:ticket-use-duotone-line" {...props}></Icon>
