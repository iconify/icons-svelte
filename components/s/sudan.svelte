<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nmibc4bxr.css';
import '../../css/p/plw4my99i.css';
import '../../css/n/ndsoh9bgy.css';
import '../../css/w/w4lc2xbcv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="nmibc4bxr"/><path class="plw4my99i"/><path class="ndsoh9bgy"/><path class="w4lc2xbcv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:sudan" {...props}></Icon>
