<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mr_hbc4nb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mr_hbc4nb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:snowman-fill" {...props}></Icon>
