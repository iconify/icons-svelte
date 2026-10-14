<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/z/zkac9ebhb.css';
import '../../css/i/iv1wfn4xs.css';
import '../../css/a/at9-cgbfo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="zkac9ebhb"/><circle class="iv1wfn4xs"/><circle class="at9-cgbfo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:users-collaboration" {...props}></Icon>
