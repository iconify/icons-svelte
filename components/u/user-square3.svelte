<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/s/stfrz6bje.css';
import '../../css/n/nwyzuufrs.css';
import '../../css/f/flmf6fbyy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="stfrz6bje"/><path class="nwyzuufrs"/><path class="flmf6fbyy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:user-square3" {...props}></Icon>
