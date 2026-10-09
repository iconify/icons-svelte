<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pj89w9bur.css';
import '../../css/n/ndtj57bce.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="pj89w9bur"/><path class="ndtj57bce"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:silo-48-bold" {...props}></Icon>
