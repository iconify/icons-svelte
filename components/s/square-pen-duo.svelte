<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i-zh-ibev.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/z/zwffu0v7l.css';
import '../../css/k/kg9s9rdnt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i-zh-ibev secondary"/><g class="dt0cm9dhy primary"><path class="zwffu0v7l"/><path class="kg9s9rdnt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:square-pen-duo" {...props}></Icon>
