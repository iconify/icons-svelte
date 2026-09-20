<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l01w4f3bq.css';
import '../../css/n/n6es8zk1y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l01w4f3bq"/><path class="n6es8zk1y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:settings-hammer" {...props}></Icon>
