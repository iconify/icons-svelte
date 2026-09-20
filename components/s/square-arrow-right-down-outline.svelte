<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hsbuoibal.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hsbuoibal"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:square-arrow-right-down-outline" {...props}></Icon>
