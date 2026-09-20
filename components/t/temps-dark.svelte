<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tr3savbbw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tr3savbbw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:temps-dark" {...props}></Icon>
