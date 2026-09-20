<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bchcmxb4x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bchcmxb4x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:stopwatch-slash" {...props}></Icon>
