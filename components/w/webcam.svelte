<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/g/g1st-obsh.css';
import '../../css/s/sm1jugbqc.css';
import '../../css/y/ytopibb5c.css';
import '../../css/c/c1ksu6uqi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><circle class="g1st-obsh"/><path class="sm1jugbqc"/><circle class="ytopibb5c"/><path class="c1ksu6uqi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:webcam" {...props}></Icon>
