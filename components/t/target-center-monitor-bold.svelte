<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oytsm6b5s.css';
import '../../css/d/dxu2gubtq.css';
import '../../css/j/j9hxiotjy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oytsm6b5s"/><path class="dxu2gubtq"/><path class="j9hxiotjy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:target-center-monitor-bold" {...props}></Icon>
