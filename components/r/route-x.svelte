<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/i/ibpzieblb.css';
import '../../css/a/aa-euubin.css';
import '../../css/d/diivyqg2d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><circle class="ibpzieblb"/><path class="aa-euubin"/><path class="diivyqg2d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:route-x" {...props}></Icon>
