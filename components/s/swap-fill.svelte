<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w0q-zublg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w0q-zublg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:swap-fill" {...props}></Icon>
