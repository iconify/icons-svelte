<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m6hm_cznf.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/j/jweyq3b2y.css';
import '../../css/h/h3x0v4biq.css';
import '../../css/u/uiq5r33vt.css';
import '../../css/v/v1j-mbbje.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m6hm_cznf secondary"/><g class="dt0cm9dhy primary"><path class="jweyq3b2y"/><circle class="h3x0v4biq"/><path class="uiq5r33vt"/><circle class="v1j-mbbje"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:sliders-vertical-duo" {...props}></Icon>
