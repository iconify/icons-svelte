<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v746_xxbt.css';
import '../../css/p/p-36ppbwo.css';
import '../../css/g/gvecnl_9x.css';
import '../../css/j/j84icywvn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="v746_xxbt"/><path class="p-36ppbwo"/><path class="gvecnl_9x"/><path class="j84icywvn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:transnistria" {...props}></Icon>
