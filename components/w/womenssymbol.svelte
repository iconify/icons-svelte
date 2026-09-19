<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c__7q5bmw.css';
import '../../css/r/rknde7bur.css';
import '../../css/b/b209fsbmb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="c__7q5bmw"/><path class="rknde7bur"/><path class="b209fsbmb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:womenssymbol" {...props}></Icon>
