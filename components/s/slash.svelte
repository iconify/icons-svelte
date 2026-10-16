<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cw--3tn7p.css';
import '../../css/u/ueef18k6a.css';
import '../../css/s/shu3xdl9q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cw--3tn7p"><path class="ueef18k6a"/><circle class="shu3xdl9q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:slash" {...props}></Icon>
