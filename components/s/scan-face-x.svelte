<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/udnf6hbtp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="udnf6hbtp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:scan-face-x" {...props}></Icon>
