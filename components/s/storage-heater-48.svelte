<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/acm28njiw.css';
import '../../css/w/w31w9xbxx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="acm28njiw"/><path class="w31w9xbxx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:storage-heater-48" {...props}></Icon>
