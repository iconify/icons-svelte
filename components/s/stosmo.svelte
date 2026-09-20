<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pgqfmz5hh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pgqfmz5hh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:stosmo" {...props}></Icon>
