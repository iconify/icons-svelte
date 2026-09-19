<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/e/eonu4gdjh.css';
import '../../css/h/h0x4ycc5d.css';
import '../../css/u/uf8pr7bxn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><circle class="eonu4gdjh"/><circle class="h0x4ycc5d"/><path class="uf8pr7bxn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="feather:shopping-cart" {...props}></Icon>
