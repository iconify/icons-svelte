<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/brrzp7bqp.css';
import '../../css/y/yswlpl_1d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="brrzp7bqp"/><path class="yswlpl_1d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:scooter-front" {...props}></Icon>
