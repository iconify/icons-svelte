<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0a9vkbzg.css';
import '../../css/v/v5ahe0b8s.css';
import '../../css/w/w_2kuaciz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="a0a9vkbzg"><path clip-rule="evenodd" class="v5ahe0b8s"/><path class="w_2kuaciz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:water-level" {...props}></Icon>
