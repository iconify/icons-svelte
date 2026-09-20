<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oa761w5ag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="oa761w5ag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:unbound-light" {...props}></Icon>
