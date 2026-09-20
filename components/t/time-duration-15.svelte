<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/phsw2obgc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="phsw2obgc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:time-duration-15" {...props}></Icon>
