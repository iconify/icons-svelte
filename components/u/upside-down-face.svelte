<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/az7hstbmu.css';
import '../../css/o/otit0l4ks.css';
import '../../css/u/uwsmjnb9k.css';
import '../../css/a/alabn_bfc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<circle class="az7hstbmu"/><circle class="otit0l4ks"/><path class="uwsmjnb9k"/><path class="alabn_bfc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:upside-down-face" {...props}></Icon>
