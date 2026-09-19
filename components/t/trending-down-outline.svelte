<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oiee_78vg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oiee_78vg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:trending-down-outline" {...props}></Icon>
