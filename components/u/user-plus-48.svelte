<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pp-_2jb1a.css';
import '../../css/b/b2zcb_1uj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="pp-_2jb1a"/><path class="b2zcb_1uj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:user-plus-48" {...props}></Icon>
