<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/e/eovavrbyd.css';
import '../../css/b/beua1hduq.css';
import '../../css/t/tzalnc8mr.css';
import '../../css/n/nunh1nbfh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="eovavrbyd"/><path class="beua1hduq"/><path class="tzalnc8mr"/><path class="nunh1nbfh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:worldwide-web-sync" {...props}></Icon>
