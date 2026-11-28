<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z_c33vrot.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/y/yb2znbbba.css';
import '../../css/z/zjsy4fbkc.css';
import '../../css/h/h89jzn-jj.css';
import '../../css/k/ksf5uac5s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary z_c33vrot"/><g class="dt0cm9dhy primary"><path class="yb2znbbba"/><path class="zjsy4fbkc"/><path class="h89jzn-jj"/><path class="ksf5uac5s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:wheelchair-duo" {...props}></Icon>
