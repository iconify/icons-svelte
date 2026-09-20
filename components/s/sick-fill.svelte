<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cy2kl1buu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cy2kl1buu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:sick-fill" {...props}></Icon>
