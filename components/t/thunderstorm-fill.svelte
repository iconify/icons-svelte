<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/clp7z2bgf.css';
import '../../css/u/u7sq-5xjs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="clp7z2bgf"/><path class="u7sq-5xjs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:thunderstorm-fill" {...props}></Icon>
