<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w03s3zj-z.css';
import '../../css/k/kc4mupbht.css';
import '../../css/j/jni1vxbzh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="w03s3zj-z"/><path class="kc4mupbht"/><path class="jni1vxbzh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:splitpro" {...props}></Icon>
