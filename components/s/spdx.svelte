<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jngd8gbrc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jngd8gbrc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:spdx" {...props}></Icon>
