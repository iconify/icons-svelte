<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sfn8rcgml.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sfn8rcgml"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:time-duration-5" {...props}></Icon>
