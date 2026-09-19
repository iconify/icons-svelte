<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qiqd9zd2t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="qiqd9zd2t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:terminal" {...props}></Icon>
