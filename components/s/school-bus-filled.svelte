<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/udwqky2ao.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="udwqky2ao"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:school-bus-filled" {...props}></Icon>
