<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pebxd96xp.css';
import '../../css/d/dfunt2aqf.css';
import '../../css/j/jopaj-b9g.css';
import '../../css/f/f60yx32es.css';
import '../../css/t/t57os687o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<rect transform="rotate(180 12 5)" class="pebxd96xp"/><rect transform="rotate(90 19 6)" class="dfunt2aqf"/><rect transform="rotate(90 5 6)" class="jopaj-b9g"/><path class="f60yx32es"/><path class="t57os687o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:upload-fill" {...props}></Icon>
