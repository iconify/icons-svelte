<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/b/bzjbox_2i.css';
import '../../css/y/yh8j1i27z.css';
import '../../css/a/ao0t6hy0j.css';
import '../../css/k/kspoj7vnd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<g class="cuyn6tgcc"><path class="bzjbox_2i"/><path class="yh8j1i27z"/><path class="ao0t6hy0j"/><path clip-rule="evenodd" class="kspoj7vnd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pencil:share-ios-circle" {...props}></Icon>
