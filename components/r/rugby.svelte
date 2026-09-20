<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/g/gj0fl5l1e.css';
import '../../css/i/i9tiws8jb.css';
import '../../css/x/xegzkobzu.css';
import '../../css/v/v4qas0osi.css';
import '../../css/g/g8hhtl19r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="gj0fl5l1e"/><rect class="i9tiws8jb"/><path class="xegzkobzu"/><rect class="v4qas0osi"/><path class="g8hhtl19r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-lab:rugby" {...props}></Icon>
