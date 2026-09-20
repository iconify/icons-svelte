<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bqq92b05g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bqq92b05g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:spectrum-line" {...props}></Icon>
