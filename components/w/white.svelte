<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cg24lgbwn.css';
import '../../css/u/ut59o-b4c.css';
import '../../css/a/acq_ddcuz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cg24lgbwn"/><path class="ut59o-b4c"/><path class="acq_ddcuz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:white" {...props}></Icon>
