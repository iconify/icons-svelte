<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/io1ow38wk.css';
import '../../css/g/g21o-jbgm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="io1ow38wk"/><path class="g21o-jbgm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:stay-inside" {...props}></Icon>
