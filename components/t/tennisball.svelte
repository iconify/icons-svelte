<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e__xz9bvx.css';
import '../../css/x/x6k9-3z8c.css';
import '../../css/s/shxaa7jyw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="e__xz9bvx"/><path class="x6k9-3z8c"/><path class="shxaa7jyw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:tennisball" {...props}></Icon>
