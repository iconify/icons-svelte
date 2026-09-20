<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/p/pod8qhbpj.css';
import '../../css/x/xtsrmvj7o.css';
import '../../css/p/p9vjoqtlo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pod8qhbpj"/><circle class="xtsrmvj7o"/><circle class="p9vjoqtlo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:scale-3-d" {...props}></Icon>
