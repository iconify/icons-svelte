<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gfdide9pn.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/o/om8qxl02a.css';
import '../../css/j/jrqqhb3az.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gfdide9pn secondary"/><g class="dt0cm9dhy primary"><path class="om8qxl02a"/><path class="jrqqhb3az"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:search-duo" {...props}></Icon>
