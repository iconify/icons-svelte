<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nc2fn6mkd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nc2fn6mkd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:xrd" {...props}></Icon>
