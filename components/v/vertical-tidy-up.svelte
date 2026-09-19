<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rinuwhlnp.css';
import '../../css/c/cdvy5kbya.css';
import '../../css/y/y06nxiblq.css';
import '../../css/t/tho7co-hn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="rinuwhlnp"><rect class="cdvy5kbya"/><rect class="y06nxiblq"/><rect class="tho7co-hn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:vertical-tidy-up" {...props}></Icon>
