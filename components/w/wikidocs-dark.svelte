<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ckent7btu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ckent7btu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:wikidocs-dark" {...props}></Icon>
