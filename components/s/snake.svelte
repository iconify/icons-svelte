<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/e/ew1t2fbjf.css';
import '../../css/i/i72j3vhdk.css';
import '../../css/v/vzk6dmbmr.css';
import '../../css/o/o48txrndz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="ew1t2fbjf"/><path class="i72j3vhdk"/><path class="vzk6dmbmr"/><path class="o48txrndz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:snake" {...props}></Icon>
