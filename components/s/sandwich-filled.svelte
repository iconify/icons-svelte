<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p7ihd2b_b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p7ihd2b_b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:sandwich-filled" {...props}></Icon>
