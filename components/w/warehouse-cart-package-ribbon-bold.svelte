<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aio2xib1e.css';
import '../../css/h/hp8gss3tw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aio2xib1e"/><path class="hp8gss3tw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:warehouse-cart-package-ribbon-bold" {...props}></Icon>
