<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i2qwjtp6x.css';
import '../../css/n/n3zvsabum.css';
import '../../css/l/l3c5_9blk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i2qwjtp6x"/><path class="n3zvsabum"/><path class="l3c5_9blk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:snx" {...props}></Icon>
