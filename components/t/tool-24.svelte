<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ucwfryzuh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ucwfryzuh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:tool-24" {...props}></Icon>
