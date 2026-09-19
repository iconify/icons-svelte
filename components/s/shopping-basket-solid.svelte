<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bh9t6fjqh.css';
import '../../css/g/g_wd5geuf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bh9t6fjqh"/><path clip-rule="evenodd" class="g_wd5geuf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:shopping-basket-solid" {...props}></Icon>
