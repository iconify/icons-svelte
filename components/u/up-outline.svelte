<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tgwvay-0n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="tgwvay-0n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:up-outline" {...props}></Icon>
