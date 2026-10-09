<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/es2omsi-m.css';
import '../../css/x/x_aucnmpg.css';
import '../../css/q/qga5sxbrw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="es2omsi-m"/><path class="x_aucnmpg"/><path class="qga5sxbrw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:tractor-20" {...props}></Icon>
