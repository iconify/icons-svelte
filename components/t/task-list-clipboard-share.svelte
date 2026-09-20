<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/m/mbk1rbcqn.css';
import '../../css/f/fv4tjzrua.css';
import '../../css/i/ii4kaebow.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="mbk1rbcqn"/><path class="fv4tjzrua"/><path class="ii4kaebow"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:task-list-clipboard-share" {...props}></Icon>
