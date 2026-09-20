<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0m25c.css';
import '../../css/g/gp600p.css';
import '../../css/b/b4_xlz.css';
import '../../css/f/f2pddx.css';
import '../../css/d/d-ash02h.css';
import '../../css/t/tr-2c6-rw.css';
import '../../css/f/fade-to-1.css';
import '../../css/d/d-9_o5mj.css';
import '../../css/d/d-s9ijad.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c gp600p"/><path class="a0m25c b4_xlz"/><path class="a0m25c f2pddx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:sun-rising-loop" {...props}></Icon>
