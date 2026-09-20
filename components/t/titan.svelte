<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/c/c69eqvbtx.css';
import '../../css/k/kut731b5g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="c69eqvbtx"/><path class="kut731b5g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:titan" {...props}></Icon>
