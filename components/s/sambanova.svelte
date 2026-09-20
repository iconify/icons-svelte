<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/ha-ru_sez.css';
import '../../css/z/zuyihimme.css';
import '../../css/o/ob81ctbsn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ha-ru_sez"/><path class="zuyihimme"/><path class="ob81ctbsn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:sambanova" {...props}></Icon>
