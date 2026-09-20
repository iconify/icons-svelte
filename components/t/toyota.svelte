<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y6zfdva6b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y6zfdva6b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:toyota" {...props}></Icon>
