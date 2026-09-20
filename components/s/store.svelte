<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hyrsg_bkj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hyrsg_bkj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:store" {...props}></Icon>
