<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/c/c27ftpu8b.css';
import '../../css/b/blxwk5baf.css';
import '../../css/j/jx7pq2b2n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="c27ftpu8b"/><path class="blxwk5baf"/><path class="jx7pq2b2n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:sneaker" {...props}></Icon>
