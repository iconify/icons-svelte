<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/b/bh3wmxbdq.css';
import '../../css/e/elti8xbhv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="bh3wmxbdq"/><circle class="elti8xbhv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:schedule" {...props}></Icon>
