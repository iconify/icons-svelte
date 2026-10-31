<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zeu8ueilu.css';
import '../../css/b/bbopbtb8a.css';
import '../../css/w/w3r7knbro.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<g display="block"><path class="zeu8ueilu"/><path class="bbopbtb8a"/><path class="w3r7knbro"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconito:spinach" {...props}></Icon>
