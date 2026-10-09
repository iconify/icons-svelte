<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ob6rb5b4d.css';
import '../../css/g/g620y8-kq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ob6rb5b4d"/><path class="g620y8-kq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:share-48-bold" {...props}></Icon>
