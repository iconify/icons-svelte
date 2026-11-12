<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/im5kk3zjb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="im5kk3zjb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:thingsboard-dark" {...props}></Icon>
