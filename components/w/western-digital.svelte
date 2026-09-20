<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kszoi5bnf.css';
import '../../css/v/vt74m5b-v.css';
import '../../css/j/jmbmabbpr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kszoi5bnf"/><path class="vt74m5b-v"/><path class="jmbmabbpr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:western-digital" {...props}></Icon>
