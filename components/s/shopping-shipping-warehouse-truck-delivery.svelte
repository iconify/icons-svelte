<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m2firwxhd.css';
import '../../css/h/hla--sikh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="m2firwxhd"/><path class="hla--sikh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:shopping-shipping-warehouse-truck-delivery" {...props}></Icon>
