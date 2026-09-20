<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/m/mmg1geb5v.css';
import '../../css/b/b2pjdqbow.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="mmg1geb5v"/><path class="b2pjdqbow"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:usdx" {...props}></Icon>
