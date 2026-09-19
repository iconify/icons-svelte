<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9cl3zbei.css';
import '../../css/s/s3--xqbfi.css';
import '../../css/m/m523p2l3w.css';
import '../../css/o/ocbtnl2hf.css';
import '../../css/j/j2sqa-b2x.css';
import '../../css/t/tjlvrohtz.css';
import '../../css/f/f9x76rbft.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="s9cl3zbei"><ellipse class="s3--xqbfi"/><path class="m523p2l3w"/><path class="ocbtnl2hf"/><path class="j2sqa-b2x"/><path class="tjlvrohtz"/><path class="f9x76rbft"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:tree-one" {...props}></Icon>
