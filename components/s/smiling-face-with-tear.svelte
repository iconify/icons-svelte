<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/az7hstbmu.css';
import '../../css/g/gikpdyyno.css';
import '../../css/o/otit0l4ks.css';
import '../../css/b/btxit0bwv.css';
import '../../css/f/f6cn9dwnw.css';
import '../../css/v/vu3r09bky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<circle class="az7hstbmu"/><path class="gikpdyyno"/><circle class="otit0l4ks"/><path class="btxit0bwv"/><path class="f6cn9dwnw"/><path class="vu3r09bky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:smiling-face-with-tear" {...props}></Icon>
