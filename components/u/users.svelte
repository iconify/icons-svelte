<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/n/n6xinhc7m.css';
import '../../css/y/yek9exb0m.css';
import '../../css/s/s8kjchbnl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><circle class="n6xinhc7m"/><path class="yek9exb0m"/><path class="s8kjchbnl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:users" {...props}></Icon>
