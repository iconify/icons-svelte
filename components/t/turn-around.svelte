<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/q/qn7kib-8y.css';
import '../../css/u/ui3uycp9j.css';
import '../../css/t/tc8jmyben.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="qn7kib-8y"/><path class="ui3uycp9j"/><path class="tc8jmyben"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:turn-around" {...props}></Icon>
