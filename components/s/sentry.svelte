<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/injzvvbgi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="injzvvbgi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:sentry" {...props}></Icon>
