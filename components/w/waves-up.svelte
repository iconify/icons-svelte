<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iz97go0-n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iz97go0-n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:waves-up" {...props}></Icon>
