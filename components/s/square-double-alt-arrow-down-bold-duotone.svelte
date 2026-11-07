<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1bfxqbht.css';
import '../../css/y/yk7g-9jxe.css';
import '../../css/p/pr-s_8yyc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n1bfxqbht"/><path class="yk7g-9jxe"/><path class="pr-s_8yyc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:square-double-alt-arrow-down-bold-duotone" {...props}></Icon>
