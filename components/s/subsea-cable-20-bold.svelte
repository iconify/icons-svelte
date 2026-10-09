<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z-lmr9bkb.css';
import '../../css/t/tk7jp-bls.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="z-lmr9bkb"/><path class="tk7jp-bls"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:subsea-cable-20-bold" {...props}></Icon>
