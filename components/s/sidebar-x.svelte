<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uykqjq0kh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uykqjq0kh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:sidebar-x" {...props}></Icon>
