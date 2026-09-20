<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/g/gzdl4jbop.css';
import '../../css/s/sjf30n3qe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="gzdl4jbop"/><path class="sjf30n3qe"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:xna" {...props}></Icon>
