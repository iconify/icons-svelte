<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qdivp_bxj.css';
import '../../css/g/gh2z3q1ep.css';
import '../../css/u/uclgd2b0i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qdivp_bxj"/><path class="gh2z3q1ep"/><path class="uclgd2b0i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:suspension-cross-bold" {...props}></Icon>
