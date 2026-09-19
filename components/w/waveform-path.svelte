<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e8yuibu_s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="e8yuibu_s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:waveform-path" {...props}></Icon>
