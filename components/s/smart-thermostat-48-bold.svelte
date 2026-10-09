<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n2neunb3u.css';
import '../../css/p/ppaig9b9i.css';
import '../../css/a/acpimzbdx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="n2neunb3u"/><path class="ppaig9b9i"/><path class="acpimzbdx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:smart-thermostat-48-bold" {...props}></Icon>
