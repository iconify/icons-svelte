<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e6vaij6_x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e6vaij6_x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:snt" {...props}></Icon>
