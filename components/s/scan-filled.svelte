<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nbny79drk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nbny79drk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:scan-filled" {...props}></Icon>
