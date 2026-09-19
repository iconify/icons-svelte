<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/w/w2lm7d1fb.css';
import '../../css/p/plxuwnb-i.css';
import '../../css/t/tioa-udgt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="w2lm7d1fb"/><path class="plxuwnb-i"/><path class="tioa-udgt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:volume-up-fill" {...props}></Icon>
