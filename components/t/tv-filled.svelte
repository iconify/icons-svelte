<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i9u5hk_ay.css';
import '../../css/e/eu62npp2u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i9u5hk_ay"/><path class="eu62npp2u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:tv-filled" {...props}></Icon>
