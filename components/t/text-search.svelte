<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/p/pcflsrbga.css';
import '../../css/d/dto95jbvb.css';
import '../../css/v/vsle8o47l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pcflsrbga"/><circle class="dto95jbvb"/><path class="vsle8o47l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:text-search" {...props}></Icon>
