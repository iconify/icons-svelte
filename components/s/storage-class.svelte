<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tnl2u0pbc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tnl2u0pbc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:storage-class" {...props}></Icon>
