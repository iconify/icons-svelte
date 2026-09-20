<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c16wjhrqn.css';
import '../../css/s/suncofbuf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="c16wjhrqn"/><path class="suncofbuf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:wifi-solid" {...props}></Icon>
