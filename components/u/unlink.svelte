<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/okzgeoz_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="okzgeoz_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:unlink" {...props}></Icon>
