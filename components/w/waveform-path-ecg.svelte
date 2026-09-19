<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b_nz6x7vn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="b_nz6x7vn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:waveform-path-ecg" {...props}></Icon>
