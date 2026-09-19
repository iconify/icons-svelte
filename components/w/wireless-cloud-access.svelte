<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/olsxm8btb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="olsxm8btb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:wireless-cloud-access" {...props}></Icon>
