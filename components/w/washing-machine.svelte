<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/r/re_3czw2d.css';
import '../../css/h/hb5frye-n.css';
import '../../css/g/gnawts8ku.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="re_3czw2d"/><path class="hb5frye-n"/><path class="gnawts8ku"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:washing-machine" {...props}></Icon>
