<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oz7vnzbwn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oz7vnzbwn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uit:stopwatch" {...props}></Icon>
