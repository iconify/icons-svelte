<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z86v6i08k.css';
import '../../css/u/uf6zebb2f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="z86v6i08k"/><path class="uf6zebb2f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:yubal-light" {...props}></Icon>
