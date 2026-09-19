<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/k/kls-7u3hg.css';
import '../../css/z/zbvr83pqm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="nrj6p8qat"><path class="kls-7u3hg"/><circle class="zbvr83pqm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bytesize:telephone" {...props}></Icon>
