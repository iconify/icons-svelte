<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/th_w9mbqn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="th_w9mbqn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:toilet-paper-off" {...props}></Icon>
