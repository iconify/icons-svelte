<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fw_pdhz4z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="fw_pdhz4z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:waveform-circle-fill" {...props}></Icon>
