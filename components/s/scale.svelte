<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/f/facftvb6k.css';
import '../../css/b/b0lbrwbnb.css';
import '../../css/a/av59wqutr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="facftvb6k"/><path class="b0lbrwbnb"/><path clip-rule="evenodd" class="av59wqutr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:scale" {...props}></Icon>
