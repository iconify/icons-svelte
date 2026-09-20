<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/errsw2beg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="errsw2beg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:screen-normal-24" {...props}></Icon>
