<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vcfac8bxc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vcfac8bxc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:steamdb-light" {...props}></Icon>
