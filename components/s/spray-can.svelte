<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aqsrx5gan.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aqsrx5gan"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:spray-can" {...props}></Icon>
