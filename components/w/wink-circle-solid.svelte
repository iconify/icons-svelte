<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p5xo13bfc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p5xo13bfc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:wink-circle-solid" {...props}></Icon>
