<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yvj1klb1m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yvj1klb1m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:wrist-watch-alt" {...props}></Icon>
