<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m_7x--shm.css';
import '../../css/l/luq2o7biq.css';
import '../../css/l/l13e8s3zd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m_7x--shm"/><path class="luq2o7biq"/><path class="l13e8s3zd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:scroll" {...props}></Icon>
