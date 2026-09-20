<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/p/pcyfrjbuz.css';
import '../../css/p/poeibnbcs.css';
import '../../css/a/a2caqccpk.css';
import '../../css/q/qg8wpjbhw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="pcyfrjbuz"/><path class="poeibnbcs"/><path clip-rule="evenodd" class="a2caqccpk"/><path class="qg8wpjbhw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:users" {...props}></Icon>
