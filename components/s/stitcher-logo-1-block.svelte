<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o-5195bzu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o-5195bzu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:stitcher-logo-1-block" {...props}></Icon>
