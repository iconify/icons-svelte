<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/ldi9lbb3u.css';
import '../../css/d/d93exubkv.css';
import '../../css/d/da_pl4pve.css';
import '../../css/j/jhxws-09i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="ldi9lbb3u"/><path class="d93exubkv"/><path class="da_pl4pve"/><path class="jhxws-09i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:suitcase-tag-bold" {...props}></Icon>
