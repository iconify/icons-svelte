<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/n/ndmrztbsq.css';
import '../../css/a/a96k7rbus.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ndmrztbsq"/><circle class="a96k7rbus"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:truck" {...props}></Icon>
