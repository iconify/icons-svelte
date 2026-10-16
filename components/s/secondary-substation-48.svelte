<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m3gk-cbll.css';
import '../../css/e/etgb51bju.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="m3gk-cbll"/><path class="etgb51bju"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:secondary-substation-48" {...props}></Icon>
