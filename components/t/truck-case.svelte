<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mt707fbnl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mt707fbnl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:truck-case" {...props}></Icon>
