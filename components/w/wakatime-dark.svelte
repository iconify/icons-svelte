<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/csw0kbbpv.css';
import '../../css/w/wf15_9b8y.css';
import '../../css/q/qiau4mbbk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":340,"height":340};
const content = `<g class="csw0kbbpv"><path clip-rule="evenodd" class="wf15_9b8y"/><path class="qiau4mbbk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:wakatime-dark" {...props}></Icon>
