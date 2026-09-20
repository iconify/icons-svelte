<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/v/vjnj9abfa.css';
import '../../css/d/d2umvjsxg.css';
import '../../css/y/yopadjb1x.css';
import '../../css/j/jhxi-trnl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="vjnj9abfa"/><circle class="d2umvjsxg"/><circle class="yopadjb1x"/><rect class="jhxi-trnl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:square-scissors" {...props}></Icon>
