<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/k/kyox24bbn.css';
import '../../css/j/ja2qzrzib.css';
import '../../css/w/wv-8vsbun.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="kyox24bbn"/><path class="ja2qzrzib"/><path clip-rule="evenodd" class="wv-8vsbun"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:text-bold-square-bold" {...props}></Icon>
