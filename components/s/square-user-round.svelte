<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/v/v8s1htbdm.css';
import '../../css/r/rus9pebka.css';
import '../../css/j/jhxi-trnl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="v8s1htbdm"/><circle class="rus9pebka"/><rect class="jhxi-trnl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:square-user-round" {...props}></Icon>
