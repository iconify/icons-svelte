<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/s/s05kiwb2w.css';
import '../../css/q/q96rhebcu.css';
import '../../css/o/o0pfhwbdc.css';
import '../../css/g/gq-pfyb5y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="s05kiwb2w"/><path class="q96rhebcu"/><path class="o0pfhwbdc"/><path clip-rule="evenodd" class="gq-pfyb5y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:skateboarding-round-outline" {...props}></Icon>
