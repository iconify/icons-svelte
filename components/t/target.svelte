<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gxji-uapf.css';
import '../../css/d/dqouzac4x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="duoicon-secondary-layer gxji-uapf"/><path class="dqouzac4x duoicon-primary-layer"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="duo-icons:target" {...props}></Icon>
