<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iz94dlk1v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="iz94dlk1v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:wechat" {...props}></Icon>
