<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dx397ftkb.css';
import '../../css/f/f5qfwg_tr.css';
import '../../css/t/tmbckpbip.css';
import '../../css/u/u9j3mpbmw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="dx397ftkb"/><circle class="f5qfwg_tr"/><path class="tmbckpbip"/><path class="u9j3mpbmw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:warning-multiple" {...props}></Icon>
