<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/f/fn7uhbbkv.css';
import '../../css/s/snsoecbzc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="fn7uhbbkv"/><path class="snsoecbzc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:tko" {...props}></Icon>
