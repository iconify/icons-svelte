<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aodbzbc2y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="aodbzbc2y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:speaker-1-solid" {...props}></Icon>
