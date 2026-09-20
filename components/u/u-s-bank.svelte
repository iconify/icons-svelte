<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g-ed46g8a.css';
import '../../css/l/l7xst3nbo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="g-ed46g8a"/><path class="l7xst3nbo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:u-s-bank" {...props}></Icon>
