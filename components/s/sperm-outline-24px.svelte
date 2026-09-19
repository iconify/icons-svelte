<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gdd28xodh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gdd28xodh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:sperm-outline-24px" {...props}></Icon>
