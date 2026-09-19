<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iyu3op__j.css';
import '../../css/j/j37e0x93k.css';
import '../../css/q/qeni9rbnv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="iyu3op__j"/><path class="j37e0x93k"/><path class="qeni9rbnv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:tag-twotone" {...props}></Icon>
