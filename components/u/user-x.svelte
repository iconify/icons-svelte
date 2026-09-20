<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/o/o2dydi33t.css';
import '../../css/t/t-u0yzblp.css';
import '../../css/e/eax14mbeg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="o2dydi33t"/><circle class="t-u0yzblp"/><path class="eax14mbeg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:user-x" {...props}></Icon>
