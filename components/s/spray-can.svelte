<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ejbb-ib3c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ejbb-ib3c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:spray-can" {...props}></Icon>
