<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wcanjw_pl.css';
import '../../css/w/wx8v4gq2k.css';
import '../../css/z/zrbbkmbeu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="wcanjw_pl"/><path class="wx8v4gq2k"/><path class="zrbbkmbeu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:vector-pen-48" {...props}></Icon>
