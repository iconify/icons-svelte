<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zd2v4sbqi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zd2v4sbqi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:startup-product-rocket-box-bold" {...props}></Icon>
