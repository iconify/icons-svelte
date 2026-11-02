<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mfgz6bbfy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mfgz6bbfy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:user-question-line" {...props}></Icon>
