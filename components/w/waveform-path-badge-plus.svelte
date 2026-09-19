<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n2e61izjw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="n2e61izjw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:waveform-path-badge-plus" {...props}></Icon>
