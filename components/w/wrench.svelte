<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mq1v61m7n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mq1v61m7n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:wrench" {...props}></Icon>
