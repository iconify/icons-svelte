<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u346-pjvt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u346-pjvt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:star-24" {...props}></Icon>
