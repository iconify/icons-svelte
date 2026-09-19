<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pu96i2m6r.css';
import '../../css/f/fbfcujy1a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="pu96i2m6r"/><path class="fbfcujy1a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:swiftformat" {...props}></Icon>
