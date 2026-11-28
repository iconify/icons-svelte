<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/h/hzz7lbhmb.css';
import '../../css/h/hr56dqbzm.css';
import '../../css/f/f7c_j4b5a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="hzz7lbhmb"/><path class="hr56dqbzm"/><path class="f7c_j4b5a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:waves-duo" {...props}></Icon>
