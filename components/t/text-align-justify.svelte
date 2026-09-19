<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ceh5_ab_e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ceh5_ab_e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:text-align-justify" {...props}></Icon>
