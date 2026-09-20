<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xq_t1dwcz.css';
import '../../css/d/deu3b0kil.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xq_t1dwcz"/><path class="deu3b0kil"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:side-peek-duotone" {...props}></Icon>
