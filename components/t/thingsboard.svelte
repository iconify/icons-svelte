<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mmz-0lb0j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mmz-0lb0j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:thingsboard" {...props}></Icon>
