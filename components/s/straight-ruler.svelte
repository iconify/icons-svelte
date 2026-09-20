<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n-lgg5lrv.css';
import '../../css/f/fbsjnybco.css';
import '../../css/q/q-97-wbjf.css';
import '../../css/m/mk2e5acas.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="n-lgg5lrv"/><path class="fbsjnybco"/><path class="q-97-wbjf"/><path class="mk2e5acas"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:straight-ruler" {...props}></Icon>
