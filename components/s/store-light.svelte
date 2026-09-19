<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/t/tgv1dsb4s.css';
import '../../css/c/c2_1yk01e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="tgv1dsb4s"/><path class="c2_1yk01e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:store-light" {...props}></Icon>
