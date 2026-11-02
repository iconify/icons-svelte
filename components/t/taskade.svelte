<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vz3bflh8i.css';
import '../../css/c/ckbkazvdl.css';
import '../../css/d/d2kvgvbvc.css';
import '../../css/m/m7kpprbdd.css';
import '../../css/b/b5rhc9t8c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<circle class="vz3bflh8i"/><circle class="ckbkazvdl"/><g class="d2kvgvbvc"><path class="m7kpprbdd"/><path class="b5rhc9t8c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:taskade" {...props}></Icon>
