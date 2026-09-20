<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/igmuzf3vd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="igmuzf3vd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:xhv" {...props}></Icon>
