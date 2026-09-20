<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g7pkxcccs.css';
import '../../css/k/k4rjlac_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g7pkxcccs"/><path class="k4rjlac_n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:sign-out-squre-duotone-line" {...props}></Icon>
