<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f5usxgrfc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f5usxgrfc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:thought-fill" {...props}></Icon>
