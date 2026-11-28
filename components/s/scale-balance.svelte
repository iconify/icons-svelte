<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/h/hp7wiib7x.css';
import '../../css/r/rxzdi1bsc.css';
import '../../css/h/hbxtj8hnk.css';
import '../../css/j/jzx1htbjk.css';
import '../../css/a/aorqrfu5e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="hp7wiib7x"/><path class="rxzdi1bsc"/><path class="hbxtj8hnk"/><path class="jzx1htbjk"/><path class="aorqrfu5e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:scale-balance" {...props}></Icon>
