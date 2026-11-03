<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l2nhrni-v.css';
import '../../css/a/az532d-fz.css';
import '../../css/z/z04drlb1l.css';
import '../../css/p/pt8thct6j.css';
import '../../css/r/rkh9jmd8r.css';
import '../../css/m/muedlcc7n.css';
import '../../css/h/h8810e80n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="l2nhrni-v"/><path class="az532d-fz"/><g class="z04drlb1l"><path class="pt8thct6j"/><path class="rkh9jmd8r"/><path class="muedlcc7n"/><path class="h8810e80n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:snake" {...props}></Icon>
