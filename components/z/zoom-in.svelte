<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/k/kb4m0fbdw.css';
import '../../css/f/flgp7zvht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="nrj6p8qat"><circle class="kb4m0fbdw"/><path class="flgp7zvht"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bytesize:zoom-in" {...props}></Icon>
