<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m9-sgc7ks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":35,"height":24};
const content = `<path class="m9-sgc7ks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:shopping-barcode" {...props}></Icon>
