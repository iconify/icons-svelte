<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ggqxp-m1t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ggqxp-m1t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:store-filled" {...props}></Icon>
