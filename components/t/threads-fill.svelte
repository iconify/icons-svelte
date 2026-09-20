<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xvq8v1bjv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xvq8v1bjv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:threads-fill" {...props}></Icon>
