<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fud2otu-j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="fud2otu-j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:switcher-outlined" {...props}></Icon>
