<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zcj0egbqd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zcj0egbqd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:save-plus" {...props}></Icon>
