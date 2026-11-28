<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/ss65wmbzo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ss65wmbzo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:shield-sparkles-solid" {...props}></Icon>
