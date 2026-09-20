<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/od77xio2s.css';
import '../../css/i/i088brsje.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="od77xio2s"/><path class="i088brsje"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:sidekiq" {...props}></Icon>
