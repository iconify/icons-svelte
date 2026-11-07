<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p6vyhu-he.css';
import '../../css/t/tm33md3wa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p6vyhu-he"/><path class="tm33md3wa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:sofa-bold" {...props}></Icon>
