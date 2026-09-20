<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wjkqr-26p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wjkqr-26p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:text" {...props}></Icon>
