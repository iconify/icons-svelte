<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/f/fr5386brj.css';
import '../../css/c/cxlsd5blc.css';
import '../../css/z/zypf8t5ce.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="fr5386brj"/><path class="cxlsd5blc"/><rect class="zypf8t5ce"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:sandwich" {...props}></Icon>
