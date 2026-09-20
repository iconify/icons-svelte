<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eq8kijp9j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eq8kijp9j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:sign-language-outline" {...props}></Icon>
