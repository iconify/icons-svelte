<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/waj_2hban.css';
import '../../css/z/z4hja-bet.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="waj_2hban"/><path class="z4hja-bet"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:xvg" {...props}></Icon>
