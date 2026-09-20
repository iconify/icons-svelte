<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/enar5ibmi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="enar5ibmi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:truck-arrow-down" {...props}></Icon>
