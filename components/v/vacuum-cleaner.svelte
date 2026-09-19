<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/q/qt79kinow.css';
import '../../css/d/db-vkwbdy.css';
import '../../css/c/c9-talbxy.css';
import '../../css/a/a9i3e_buh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="qt79kinow"/><path class="db-vkwbdy"/><circle class="c9-talbxy"/><path class="a9i3e_buh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:vacuum-cleaner" {...props}></Icon>
