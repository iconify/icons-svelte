<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/byo-9pbvk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="byo-9pbvk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:sorting-left-duotone" {...props}></Icon>
