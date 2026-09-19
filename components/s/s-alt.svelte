<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sws6u3btr.css';
import '../../css/b/blhityb7b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="sws6u3btr"/><path class="blhityb7b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:s-alt" {...props}></Icon>
