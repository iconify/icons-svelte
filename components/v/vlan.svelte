<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nym22vbim.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="nym22vbim"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:vlan" {...props}></Icon>
