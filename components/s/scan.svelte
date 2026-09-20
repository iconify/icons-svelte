<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/ws0cxaczd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ws0cxaczd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:scan" {...props}></Icon>
