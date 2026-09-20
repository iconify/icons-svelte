<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zi2twwbvj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zi2twwbvj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:shield-alert" {...props}></Icon>
