<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/u/uo05yyjpj.css';
import '../../css/f/fm01msbde.css';
import '../../css/g/g1o6erbxj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><circle class="uo05yyjpj"/><path class="fm01msbde"/><path class="g1o6erbxj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:ubuntu" {...props}></Icon>
