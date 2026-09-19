<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/skz3znhmm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="skz3znhmm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:swipe-left-02" {...props}></Icon>
