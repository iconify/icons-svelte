<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wq1_b0oru.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wq1_b0oru"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:sausage" {...props}></Icon>
