<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u3qcfitqq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":456};
const content = `<path class="u3qcfitqq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:switch" {...props}></Icon>
