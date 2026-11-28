<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/y/yzkly3sbo.css';
import '../../css/w/w9rxeebaz.css';
import '../../css/f/fof5_7bik.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="yzkly3sbo"/><path class="w9rxeebaz"/><path class="fof5_7bik"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:unfold-vertical-duo" {...props}></Icon>
