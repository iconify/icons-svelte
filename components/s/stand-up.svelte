<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o93lq-byo.css';
import '../../css/v/v-f79accf.css';
import '../../css/p/pjeackbyg.css';
import '../../css/b/b0u8-bb3i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="o93lq-byo"><path class="v-f79accf"/><path class="pjeackbyg"/><circle class="b0u8-bb3i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:stand-up" {...props}></Icon>
