<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qhqjqqb2f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qhqjqqb2f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:share" {...props}></Icon>
