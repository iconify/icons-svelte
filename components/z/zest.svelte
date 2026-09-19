<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/j/jbcquhcbm.css';
import '../../css/m/md286fbip.css';
import '../../css/h/hjyf7p0pe.css';
import '../../css/u/ulnqukbhs.css';
import '../../css/m/mevz94bei.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="bi12bsetm"><circle class="jbcquhcbm"/><g class="md286fbip"><path class="hjyf7p0pe"/><path class="ulnqukbhs"/><path class="mevz94bei"/></g></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency-color:zest" {...props}></Icon>
