<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lwkonctys.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="lwkonctys"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:travisci" {...props}></Icon>
