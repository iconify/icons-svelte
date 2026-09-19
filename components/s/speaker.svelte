<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o29qi7b6u.css';
import '../../css/d/dwh0e6bgs.css';
import '../../css/p/pt-pcmp0v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o29qi7b6u"/><path class="dwh0e6bgs"/><path class="pt-pcmp0v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:speaker" {...props}></Icon>
