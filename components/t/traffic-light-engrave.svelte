<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/g/gwth-_hib.css';
import '../../css/j/jd7su4bny.css';
import '../../css/o/o2v087bye.css';
import '../../css/h/hqyg-9bir.css';
import '../../css/p/p0q2sxjnz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="gwth-_hib wm-k"/><path class="jd7su4bny wm-a"/><path class="o2v087bye wm-shadow"/><path class="hqyg-9bir wm-k"/><path class="p0q2sxjnz wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:traffic-light-engrave" {...props}></Icon>
