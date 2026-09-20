<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0m25c.css';
import '../../css/g/gp600p.css';
import '../../css/i/i5k6wm.css';
import '../../css/j/j0_w7i.css';
import '../../css/d/d-ash02h.css';
import '../../css/f/fade-to-1.css';
import '../../css/d/d-9_o5mj.css';
import '../../css/d/d-s9ijad.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c gp600p"/><path class="a0m25c i5k6wm"/><path class="a0m25c j0_w7i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:sun-rising" {...props}></Icon>
