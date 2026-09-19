<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uybs10bee.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uybs10bee"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:sun-01" {...props}></Icon>
