<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ixeh-hb2u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ixeh-hb2u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:shop-solid" {...props}></Icon>
