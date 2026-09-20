<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wp_u8u75x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wp_u8u75x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:shopping-bag-solid" {...props}></Icon>
