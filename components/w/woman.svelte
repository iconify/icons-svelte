<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bcyvurbju.css';
import '../../css/z/zy09reb_v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="bcyvurbju"/><path class="zy09reb_v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:woman" {...props}></Icon>
