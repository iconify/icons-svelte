<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ppyuwyb2g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="ppyuwyb2g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:time-zone" {...props}></Icon>
