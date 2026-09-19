<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/d/dhvj8qb5m.css';
import '../../css/u/ur_5djb1t.css';
import '../../css/i/i8h-plf8e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="dhvj8qb5m"/><path class="ur_5djb1t"/><path class="i8h-plf8e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:vintage-clock" {...props}></Icon>
