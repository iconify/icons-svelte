<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vfezq7azm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vfezq7azm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:shield-user-round" {...props}></Icon>
