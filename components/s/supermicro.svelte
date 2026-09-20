<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qjly1mbwe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qjly1mbwe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:supermicro" {...props}></Icon>
