<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d1d_dd5jm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d1d_dd5jm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:square-help-round" {...props}></Icon>
