<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b16bxbgpf.css';
import '../../css/y/yyxdkxbnm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":180};
const content = `<path class="b16bxbgpf"/><path class="yyxdkxbnm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:youtube" {...props}></Icon>
