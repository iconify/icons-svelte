<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kr9fsfb8t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":1792};
const content = `<path class="kr9fsfb8t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:window-restore" {...props}></Icon>
