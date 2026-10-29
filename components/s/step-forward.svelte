<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ot621egsn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ot621egsn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:step-forward" {...props}></Icon>
