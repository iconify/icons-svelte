<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ifo9zfbnz.css';
import '../../css/z/zhoth9btb.css';
import '../../css/p/p5qfpwqcv.css';
import '../../css/z/ztaoll0si.css';
import '../../css/i/ilt-swa-p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ifo9zfbnz"/><path class="zhoth9btb"/><path class="p5qfpwqcv"/><path class="ztaoll0si"/><path class="ilt-swa-p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:translation-bold" {...props}></Icon>
