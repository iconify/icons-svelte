<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/v/vk5gw_r8i.css';
import '../../css/v/vqvyaqdbj.css';
import '../../css/t/tpp0pbuxr.css';
import '../../css/g/guxqo8m1z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vk5gw_r8i"/><path class="vqvyaqdbj"/><path class="tpp0pbuxr"/><path class="guxqo8m1z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:security-card" {...props}></Icon>
