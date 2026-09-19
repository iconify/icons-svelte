<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v92du4b9z.css';
import '../../css/l/l7b_ym2oe.css';
import '../../css/q/qw0bgzezr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="v92du4b9z"/><path class="l7b_ym2oe"/><path class="qw0bgzezr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:thunderstorm-severe" {...props}></Icon>
