<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mq1km7b-n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mq1km7b-n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:volume-minus" {...props}></Icon>
