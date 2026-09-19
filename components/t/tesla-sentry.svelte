<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i9t0qvb5p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i9t0qvb5p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:tesla-sentry" {...props}></Icon>
