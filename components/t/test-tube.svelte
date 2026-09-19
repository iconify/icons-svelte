<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pddcmsbna.css';
import '../../css/d/dn0mdxfaw.css';
import '../../css/c/cno_h1bwt.css';
import '../../css/r/rgii3wb9y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="pddcmsbna"/><circle class="dn0mdxfaw"/><circle class="cno_h1bwt"/><path class="rgii3wb9y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:test-tube" {...props}></Icon>
