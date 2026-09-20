<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m9hkrgbxb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="m9hkrgbxb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:table-add-row-below" {...props}></Icon>
