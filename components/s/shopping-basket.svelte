<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/np0e99fbv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="np0e99fbv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:shopping-basket" {...props}></Icon>
