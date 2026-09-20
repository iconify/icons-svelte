<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/ml3alvz3j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ml3alvz3j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:view-module" {...props}></Icon>
