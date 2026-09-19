<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0a9vkbzg.css';
import '../../css/e/eg8wnsuni.css';
import '../../css/p/p7p86-b-z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="a0a9vkbzg"><path class="eg8wnsuni"/><path class="p7p86-b-z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:sleep" {...props}></Icon>
