<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dagcc8buf.css';
import '../../css/n/ny7q1b0qs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dagcc8buf"/><path class="ny7q1b0qs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:target-user" {...props}></Icon>
