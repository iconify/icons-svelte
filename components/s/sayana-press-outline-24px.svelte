<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p4ra0ur2b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="p4ra0ur2b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:sayana-press-outline-24px" {...props}></Icon>
