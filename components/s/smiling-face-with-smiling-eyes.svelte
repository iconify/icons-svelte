<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/az7hstbmu.css';
import '../../css/z/z04drlb1l.css';
import '../../css/s/sgor8wbzm.css';
import '../../css/f/ff7mynj7b.css';
import '../../css/h/h3w_jji0j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<circle class="az7hstbmu"/><g class="z04drlb1l"><circle class="sgor8wbzm"/><path class="ff7mynj7b"/><path class="h3w_jji0j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:smiling-face-with-smiling-eyes" {...props}></Icon>
