<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eq37k5_mx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eq37k5_mx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:wpexplorer" {...props}></Icon>
