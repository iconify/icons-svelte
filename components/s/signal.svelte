<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wv05x2o-m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":896,"height":1024};
const content = `<path class="wv05x2o-m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:signal" {...props}></Icon>
