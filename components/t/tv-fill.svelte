<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qvsmmt4aw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="qvsmmt4aw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:tv-fill" {...props}></Icon>
