<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gzdld6fdb.css';
import '../../css/a/a1kinh57h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="gzdld6fdb"/><circle class="a1kinh57h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:vlan-ibm" {...props}></Icon>
