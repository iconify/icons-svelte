<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/slaia1q8b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="slaia1q8b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:sst" {...props}></Icon>
