<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k71mgzbis.css';
import '../../css/a/a3siao3xy.css';
import '../../css/z/z4sj3ixdz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="k71mgzbis"/><path class="a3siao3xy"/><path class="z4sj3ixdz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:server-check-48" {...props}></Icon>
