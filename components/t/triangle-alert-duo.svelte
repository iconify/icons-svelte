<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y7nnwqbzr.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/c/cx-db_bvv.css';
import '../../css/r/re_xy969r.css';
import '../../css/o/o03gqvbuw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary y7nnwqbzr"/><g class="dt0cm9dhy primary"><path class="cx-db_bvv"/><path class="re_xy969r"/><path class="o03gqvbuw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:triangle-alert-duo" {...props}></Icon>
