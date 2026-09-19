<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/l/llac4cb8o.css';
import '../../css/b/b4rmc7hja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="llac4cb8o"/><path class="b4rmc7hja"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:wechat-solid" {...props}></Icon>
