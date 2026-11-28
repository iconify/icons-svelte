<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bk0_bffgj.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/v/viag24bxx.css';
import '../../css/n/nnw1_fa2c.css';
import '../../css/q/qjzyurbpi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bk0_bffgj secondary"/><g class="dt0cm9dhy primary"><path class="viag24bxx"/><path class="nnw1_fa2c"/><path class="qjzyurbpi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:tag-off-duo" {...props}></Icon>
