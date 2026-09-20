<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/p/pra9yqb_a.css';
import '../../css/h/hu1yjobuk.css';
import '../../css/g/g_-f5xbnn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="pra9yqb_a"/><path class="hu1yjobuk"/><path class="g_-f5xbnn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:voice-id-approved" {...props}></Icon>
