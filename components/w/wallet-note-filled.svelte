<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/utnljdo3d.css';
import '../../css/p/pw5u487pl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="utnljdo3d"/><path class="pw5u487pl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:wallet-note-filled" {...props}></Icon>
