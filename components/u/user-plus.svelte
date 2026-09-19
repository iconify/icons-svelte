<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/f/fnh9tclws.css';
import '../../css/u/up4t6029a.css';
import '../../css/l/l3fk2pbmc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="fnh9tclws"/><circle class="up4t6029a"/><path class="l3fk2pbmc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="feather:user-plus" {...props}></Icon>
