<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hc6omccsd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hc6omccsd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:tent-solid" {...props}></Icon>
