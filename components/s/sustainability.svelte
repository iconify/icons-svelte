<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nln80aciw.css';
import '../../css/k/k01r6evgn.css';
import '../../css/k/kk0hmeb4g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="nln80aciw"/><path class="k01r6evgn"/><path class="kk0hmeb4g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:sustainability" {...props}></Icon>
