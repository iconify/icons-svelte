<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cb5rkrnep.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cb5rkrnep"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:xdotorg" {...props}></Icon>
