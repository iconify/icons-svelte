<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dwaoqfrmu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dwaoqfrmu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:table-rows-filled" {...props}></Icon>
