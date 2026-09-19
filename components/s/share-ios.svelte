<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/e/e8vs1tblt.css';
import '../../css/z/zi7afo3ec.css';
import '../../css/p/pbuz9tema.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="e8vs1tblt"/><path class="zi7afo3ec"/><path class="pbuz9tema"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:share-ios" {...props}></Icon>
