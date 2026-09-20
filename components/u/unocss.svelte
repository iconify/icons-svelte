<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k-q81khvm.css';
import '../../css/t/tqfna8b9r.css';
import '../../css/n/nxg4_6n1c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<circle class="k-q81khvm"/><path class="tqfna8b9r"/><path class="nxg4_6n1c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:unocss" {...props}></Icon>
