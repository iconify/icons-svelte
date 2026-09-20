<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/z/zfdr3yxhp.css';
import '../../css/g/ghya2pbow.css';
import '../../css/h/hhc96f81o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="zfdr3yxhp"/><circle class="ghya2pbow"/><rect class="hhc96f81o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:user-lock" {...props}></Icon>
