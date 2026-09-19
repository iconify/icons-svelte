<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/p/poft66hgr.css';
import '../../css/p/p-r-ng-lg.css';
import '../../css/g/gz_3a5b5x.css';
import '../../css/z/z544yj0jp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><rect transform="matrix(0 -1 -1 0 21 22)" class="poft66hgr"/><path class="p-r-ng-lg"/><path class="gz_3a5b5x"/><path class="z544yj0jp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:x-ray" {...props}></Icon>
