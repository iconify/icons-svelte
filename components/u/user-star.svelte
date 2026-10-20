<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hfhurn1ro.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hfhurn1ro"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:user-star" {...props}></Icon>
