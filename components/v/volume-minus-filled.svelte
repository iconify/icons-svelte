<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iw1iew.css';
import '../../css/r/rbi7zg.css';
import '../../css/n/nbeutd.css';
import '../../css/s/so-from-34.css';
import '../../css/f/fill-to-1.css';
import '../../css/s/so-to-0.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iw1iew rbi7zg"/><path class="iw1iew nbeutd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:volume-minus-filled" {...props}></Icon>
