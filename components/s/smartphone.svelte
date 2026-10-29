<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fx7eavlwm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fx7eavlwm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:smartphone" {...props}></Icon>
