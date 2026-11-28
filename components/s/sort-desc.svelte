<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cr8__mnxv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cr8__mnxv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:sort-desc" {...props}></Icon>
