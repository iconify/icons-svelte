<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/flo9z28mp.css';
import '../../css/n/ntt7ilb9v.css';
import '../../css/k/kwk2estza.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="flo9z28mp"/><path class="ntt7ilb9v"/><path class="kwk2estza"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:windmill" {...props}></Icon>
