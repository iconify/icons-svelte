<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zoug98bec.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/f/f9sm5sb1s.css';
import '../../css/a/at5jq4jfg.css';
import '../../css/t/t_be4jbjc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary zoug98bec"/><g class="dt0cm9dhy primary"><path class="f9sm5sb1s"/><path class="at5jq4jfg"/><path class="t_be4jbjc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:star-medal-duo" {...props}></Icon>
