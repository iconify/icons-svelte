<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nr5nhmbcw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nr5nhmbcw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:voice-fill" {...props}></Icon>
