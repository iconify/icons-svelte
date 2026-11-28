<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zyg5edm9y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zyg5edm9y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:user-circle-plus" {...props}></Icon>
