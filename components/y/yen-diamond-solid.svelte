<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tld_fzzem.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tld_fzzem"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:yen-diamond-solid" {...props}></Icon>
