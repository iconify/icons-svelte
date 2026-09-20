<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ob6wv6w5p.css';
import '../../css/o/olze3bcsd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ob6wv6w5p"/><path clip-rule="evenodd" class="olze3bcsd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:stopwatch" {...props}></Icon>
