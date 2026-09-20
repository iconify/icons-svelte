<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jmn0rkbxk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="jmn0rkbxk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="map:ski-jumping" {...props}></Icon>
