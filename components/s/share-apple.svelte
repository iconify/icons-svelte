<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bbgvppbqc.css';
import '../../css/w/w1c22wekr.css';
import '../../css/l/l8y7zreew.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="bbgvppbqc"/><path class="w1c22wekr"/><path class="l8y7zreew"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ei:share-apple" {...props}></Icon>
