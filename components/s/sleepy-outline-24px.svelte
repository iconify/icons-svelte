<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/l132zcc0f.css';
import '../../css/b/bduw573rj.css';
import '../../css/g/gnezv3kba.css';
import '../../css/d/dsfjv5buk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="l132zcc0f"/><path class="bduw573rj"/><path clip-rule="evenodd" class="gnezv3kba"/><path class="dsfjv5buk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:sleepy-outline-24px" {...props}></Icon>
