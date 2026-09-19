<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nveaw9mgu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":424,"height":448};
const content = `<path class="nveaw9mgu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:spinner" {...props}></Icon>
