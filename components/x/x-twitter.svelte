<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jdkhh5u2a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jdkhh5u2a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:x-twitter" {...props}></Icon>
