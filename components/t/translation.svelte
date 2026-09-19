<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cwna3ebpo.css';
import '../../css/v/vfiksfbii.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="cwna3ebpo"/><path class="vfiksfbii"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:translation" {...props}></Icon>
