<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/n/n35mfrb1w.css';
import '../../css/c/crlngeb_w.css';
import '../../css/j/jssk5pctd.css';
import '../../css/v/voxh6ccdb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":25};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="n35mfrb1w"/><path class="crlngeb_w"/><path class="jssk5pctd"/><path class="voxh6ccdb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cuida:sort-ascending-duotone" {...props}></Icon>
