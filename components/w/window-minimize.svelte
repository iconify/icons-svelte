<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gxtrb1b8k.css';
import '../../css/h/ho146fqck.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gxtrb1b8k"/><path class="ho146fqck"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:window-minimize" {...props}></Icon>
