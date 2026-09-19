<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iw3g69bqk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="iw3g69bqk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:speech-balloon" {...props}></Icon>
