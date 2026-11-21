<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/d/d_djo3b2e.css';
import '../../css/k/k5lxk7bym.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="d_djo3b2e"/><path class="k5lxk7bym"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wordpress:update" {...props}></Icon>
